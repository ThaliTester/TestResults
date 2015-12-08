#### Test 50650278b1aec71_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/Finsky  ( 4925): [1] 5.onFinished: Scheduling replication attempt 5.
,D/AndroidRuntime( 6173): 
D/AndroidRuntime( 6173): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6173): CheckJNI is OFF
D/AndroidRuntime( 6173): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1068): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1915): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1068): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1068): setTaskToReturnTo : TaskRecord{35aa1744 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1068): setTaskToReturnTo : TaskRecord{35aa1744 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1068): AppWindowTokenEx init.. 
E/GBMv2   (  353): DFP En is all cleared set to be enabled
I/ActivityManager( 1068): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6193 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6173): Shutting down VM
V/ActivityManager( 1068): Display changed displayId=0
D/DSDPConnection( 1826): Display #0 changed.
D/SplitWindowPolicy( 1915): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1915): topRunningActivity=ActivityInfo{3b81ce6b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1915): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1915): topRunningActivity=ActivityInfo{34ebadc8 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6193): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6193): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6193): Loading: webviewchromium
I/LibraryLoader( 6193): Time to load native libraries: 4 ms (timestamps 6143-6147)
I/LibraryLoader( 6193): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6193): Binding Chromium to main looper Looper (main, tid 1) {15f62b24}
I/LibraryLoader( 6193): Expected native library version number "",actual native library version number ""
I/chromium( 6193): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6193): Initializing chromium process, renderers=0
W/art     ( 6193): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6193): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6193): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6193): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6193): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  313): registerClient() client 0xb1184f00, uid 10311
D/BluetoothManagerService( 1068): Message: 20
D/BluetoothManagerService( 1068): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ce7d9ae:true
I/Adreno-EGL( 6193): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6193): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6193): Build Date: 12/12/14 금
I/Adreno-EGL( 6193): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6193): Remote Branch: 
I/Adreno-EGL( 6193): Local Patches: 
I/Adreno-EGL( 6193): Reconstruct Branch: 
D/BluetoothAdapter( 6193): 483231373: getState() :  mService = null. Returning STATE_OFF
I/art     ( 1068): Explicit concurrent mark sweep GC freed 29818(1395KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.082ms total 136.482ms
W/chromium( 6193): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6193): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/ActivityManager( 1068): Activity pause timeout for ActivityRecord{2f1ad02d u0 com.test.thalitest/.MainActivity t4}
W/art     ( 6193): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6193): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6193): CordovaWebView is running on device made by: LGE
W/art     ( 6193): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6193): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6193): Render dirty regions requested: true
I/OpenGLRenderer( 6193): Initialized EGL, version 1.4
D/OpenGLRenderer( 6193): Enabling debug mode 0
D/Atlas   ( 6193): Validating map...
D/SplitWindow( 1068): check instance of lgWin Window{3b2b23f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6193): LgDataFeature() Constructor: none
D/LgDataFeature( 6193): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1068): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1068): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1068): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1068): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1068): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@31f9d591,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1068): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1449): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1449): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1449):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1449): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1068): Displayed com.test.thalitest/.MainActivity: +669ms (total +762ms)
I/Timeline( 1068): Timeline: Activity_windows_visible id: ActivityRecord{2f1ad02d u0 com.test.thalitest/.MainActivity t4} time:276639
I/Timeline( 6193): Timeline: Activity_idle id: android.os.BinderProxy@1e7a2cfd time:276644
I/chromium( 6193): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6193): 
D/JsMessageQueue( 6193): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6193): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435088128
D/JX-Cordova( 6193): jxcore cordova android initializing
,E/GBMv2   (  353): DFP En is all cleared set to be enabled
E/GBMv2   (  353): Set value is all cleared set the max
I/GBMv2   (  353): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6193): Initializing JXcore engine
W/jxcore-log( 6193): JXcore engine is ready
,W/jxcore-log( 6193): Starting JXcore engine
W/.test.thalitest( 6193): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[8384]" dev="sockfs" ino=8384 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6193): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6193): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8590]" dev="sockfs" ino=8590 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6193): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6193): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[30019]" dev="sockfs" ino=30019 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/art     ( 6193): Background sticky concurrent mark sweep GC freed 123900(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.595ms total 107.861ms
,W/jxcore-log( 6193): Platform android
W/jxcore-log( 6193): 
W/jxcore-log( 6193): Process ARCH arm
W/jxcore-log( 6193): 
,I/jxcore-log( 6193): JXcore Cordova bridge is ready!
I/jxcore-log( 6193): 
W/jxcore-log( 6193): JXcore engine is started
,E/jxcore  ( 6193): Error!: missing ) after argument list
E/jxcore  ( 6193): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6193): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6193): 
I/chromium( 6193): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager( 1068): Killing 5507:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1068): failed to open /acct/uid_10011/pid_5507/cgroup.procs: No such file or directory
,W/PluginManager( 6193): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 24ms. Plugin should use CordovaInterface.getThreadPool().,
E/GBMv2   (  353): DFP En is all cleared set to be enabled
,D/SplitWindowPolicy( 1915): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1915): topRunningActivity=ActivityInfo{7fc1e61 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1915): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1915): topRunningActivity=ActivityInfo{17a0ad86 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
W/ScreenOrientationListener( 6193): Removing an inexistent observer!
I/[LGHome]EVENT( 2008): [Launcher.java:5338:onStart()]onStart
,I/[LGHome]EVENT( 2008): [Launcher.java:903:onResume()]onResume
D/InputDispatcher( 1068): Window went away: Window{3b2b23f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/[LGHome]EVENT( 2008): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2008): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/ActionManagerService( 1880): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2008): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 2706): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2008): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2008): [Launcher.java:1056:onResume()]onResume end
I/ActivityManager( 1068): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6270 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2008): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1880): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2008): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/LIA_Informant_ActionManagerMessageHandler( 2706): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2706): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2008): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2008): , create_time: 1430558575574
I/GBoardWebViewUtils( 2008): , expire_time: 0
I/GBoardWebViewUtils( 2008): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2008): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2008): , display: false
I/GBoardWebViewUtils( 2008): , animation: false }
I/GBoardWebViewUtils( 2008): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2008): , create_time: 1430558575600
I/GBoardWebViewUtils( 2008): , expire_time: 0
I/GBoardWebViewUtils( 2008): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2008): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2008): , display: false
I/GBoardWebViewUtils( 2008): , animation: false }
I/GBoardWebViewUtils( 2008): checkExpiredAndRemoveCard() card: GBoardCard = { id: new_feature_1111111111111_1449584869051
I/GBoardWebViewUtils( 2008): , create_time: 1449584869233
I/GBoardWebViewUtils( 2008): , expire_time: 0
I/GBoardWebViewUtils( 2008): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2008): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2008): , display: false
I/GBoardWebViewUtils( 2008): , animation: false }
D/WallpaperManager( 2008): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,I/SystemUI[Framework]( 1068): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
D/PhoneStatusBar( 1449): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
W/PhoneWindowManagerEx( 1068): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1068): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1068): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1068): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@31f9d591,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1068): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1449): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1449):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1449): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]GBoardWebView( 2008): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/art     ( 6270): Almond Protected OAT
,I/[LGHome]EVENT( 2008): [Launcher.java:5349:onStop()]onStop
,D/WeatherApplication( 6270): removeAccount
D/WeatherApplication( 6270): Account.length = 0
E/WeatherApplication( 6270): OPERATOR:OPEN
D/WeatherAncestor( 6270): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:30:38
D/Weather.Utils( 6270): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6270): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6270): 2 : This is isUpdating : false
D/Weather.Utils( 6270): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6270): 2 : All the weather widget is gone.
D/WeatherAncestor( 6270): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:30:38
I/ActivityManager( 1068): Killing 5528:com.android.contacts/u0a19 (adj 15): empty #17
,I/[LGHome]Launcher.Model( 2008): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2008): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2008): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2008): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2008): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2008): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/libprocessgroup( 1068): failed to open /acct/uid_10019/pid_5528/cgroup.procs: No such file or directory
I/Timeline( 1068): Timeline: Activity_windows_visible id: ActivityRecord{4688a2d u0 com.lge.launcher2/.Launcher t3} time:279454
,I/[LGHome]Launcher.Model( 2008): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2008): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]Launcher( 2008): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2008): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2008): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2008): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 2008): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2008): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/[Concierge]Service( 2591): onStartCommand(). Type : 8
D/[Concierge]Service( 2591): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2591): Update widget ID : 11
D/[Concierge]WidgetView( 2008): change position of spinner
I/[Concierge]WidgetView( 2008): initWebView(). Time : 1449595838668
D/[Concierge]Service( 2591): onStartCommand(). Type : 0
,I/[Concierge]WebView( 2008): Return exist ConciergeWebView. Reuse : 947497044
D/[Concierge]WidgetView( 2008): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2008): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2008): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3ce0303
I/[LGHome]EVENT( 2008): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2008): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2008): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2008): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2008): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2008): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/[Concierge]WidgetView( 2008): Widget kill message received. Destory myself. My : 1449595587396, New one : 1449595838668
D/[Concierge]WidgetView( 2008): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2008): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/[LGHome]Launcher( 2008): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2008): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2008): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2008): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2008): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
,I/[LGHome]EVENT( 2008): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2008): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2008): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2008): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2008): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2008): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,I/[LGHome]Launcher( 2008): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2008): Timeline: Activity_idle id: android.os.BinderProxy@32239ebd time:279709
,I/chromium( 2008): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2008): onReloaded()
,I/GBoardWebViewClient( 2008): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2706): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2706): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/ActionManagerService( 1880): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2706): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2706): onEvent() : ACTION_BOARD_ENABLED
I/ActivityManager( 1068): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6316 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/ActionManagerService( 1880): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2706): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2706): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2706): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2706): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2706): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2008): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2008): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,D/GBoardUriUtils( 2008): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2008): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2008): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature2.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2008): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature2.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,V/FormManager( 6316): BoardCategory : com.lge.intent.category.gboard.MYWELLNESS, true
,I/ActivityManager( 1068): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6349 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 6316): Network not available. Please check & try again.
V/FormManager( 6316): Network unavailable.
V/FormManager( 6316): Network unavailable.
,I/ActivityManager( 1068): Killing 5838:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1068): failed to open /acct/uid_10023/pid_5838/cgroup.procs: No such file or directory
,E/ActivityThread( 6349): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6349): No ProfileInfo entries
I/LG Account v2.2( 6349): isEnabled: false
I/Feature ( 6349): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6349): [Lifetracker]Country: EU
I/Feature ( 6349): [Lifetracker]Operator: OPEN
I/Feature ( 6349): [Lifetracker]Ranking support: false
I/Feature ( 6349): [Lifetracker]Comfort support: false
I/Feature ( 6349): [Lifetracker]Accessory: true
I/Feature ( 6349): [Lifetracker]Health device: true
I/Feature ( 6349): [Lifetracker]Extra Pedometer: false
I/Feature ( 6349): [Lifetracker]Blood glucose device: false
I/Feature ( 6349): [Lifetracker]Device Number: 3
,D/CoreEventReceiver( 6349): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
I/GBoardStateUtil( 6349): [GBoardStateUtil] isEnableLGHealthofGBoard : true
I/CoreEventReceiver( 6349): gboardCategory : com.lge.intent.category.gboard.MYWELLNESS, gboardState : true
,I/ActivityManager( 1068): Killing 5554:com.android.gallery3d/u0a27 (adj 15): empty #17
I/GBoardtInterface( 2008): exportHTML()
,I/LIA_Informant_LogCore( 2706): LIA Log setTagPrefix - prefix : LIA_Informant_
,I/LIA_Informant_BoardCondition( 2706): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
I/LIA_MrGDBLogger_LogCore( 2706): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2706): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
W/libprocessgroup( 1068): failed to open /acct/uid_10027/pid_5554/cgroup.procs: No such file or directory
,I/LIA_S4URecommender_LogCore( 2706): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
,I/LIA_S4URecommender_BoardCondition( 2706): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
I/GBoardtInterface( 2008): exportHTML()
D/CoreEventReceiver( 6349): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
,V/FormManager( 6316): BoardCategory : com.lge.intent.category.gboard.DOYOUKNOW, true
I/GBoardStateUtil( 6349): [GBoardStateUtil] isEnableLGHealthofGBoard : true
I/CoreEventReceiver( 6349): gboardCategory : com.lge.intent.category.gboard.DOYOUKNOW, gboardState : true
I/LIA_Informant_LogCore( 2706): LIA Log setTagPrefix - prefix : LIA_Informant_
I/LIA_Informant_BoardCondition( 2706): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
,I/GBoardtInterface( 2008): exportHTML()
I/LIA_Informant_BoardStateUtil( 2706): defaultHomePackage : com.lge.launcher2
D/LIA_Informant_TaskActivator( 2706): DefaultHomeCondition is satisfied
W/FormManager( 6316): Network not available. Please check & try again.
V/FormManager( 6316): Network unavailable.
I/LIA_Informant_BoardStateUtil( 2706): isEnabledConciergeBoard() : count > 0 - true
D/LIA_Informant_TaskActivator( 2706): BoardCondition is satisfied
W/LIA_Informant_TaskActivator( 2706): setActivation() : Informant Task - ACTIVATION
,D/LIA_Informant_LGIntelligentAgent( 2706): activateLIAService : Informant / true
I/LIA_Informant_LIATaskLoader( 2706): getTaskSdkClassName : com.lge.ia.LIAInformant
D/LIA_Informant_LIATaskLoader( 2706): classLoad - TargetClass : com.lge.ia.LIAInformant
V/FormManager( 6316): Network unavailable.
I/LIA_Informant_LIATaskLoader( 2706): createLIAService - Success
I/LIA_Informant_LGIntelligentAgent( 2706): activateLIAService : startService success. (You may need to check whether its property has changed or not!)
,D/LIA_Informant_LIARemoteService( 2706): onStartCommand() : LIARemoteService started! - (Id :5), Intent { act=com.lge.ia.task.informant pkg=com.lge.ia.task.informant (has extras) }
I/LIA_Informant_InformantService( 2706): isNowInActivationCondition()
I/LIA_Informant_BoardStateUtil( 2706): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_ActivationConditionHandler( 2706): ActivationConditionHandler : LGHome condition is true
I/LIA_Informant_BoardStateUtil( 2706): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ActivationConditionHandler( 2706): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 2706): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
I/LIA_Informant_InformantService( 2706): getTaskPropertiesAtFirstStarting()
D/LIA_Informant_LIARemoteService( 2706): --> LIA task activation intent from com.lge.ia.task.informant for Informant(activation: true)
D/LIA_Informant_LIARemoteService( 2706): updateTaskProperty() : 
I/LIA_Informant_LIARemoteService( 2706): --> LIA task activation intent from com.lge.ia.task.informant, but it's same as the current setting or couldn't chagne it so just passed !! (Informant activation : true)
I/LIA_MrGDBLogger_LogCore( 2706): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2706): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
,I/LIA_S4URecommender_LogCore( 2706): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_BoardCondition( 2706): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
E/GBMv2   (  353): DFP En is all cleared set to be enabled
E/GBMv2   (  353): Set value is all cleared set the max
I/GBMv2   (  353): DFP Enabled. Ignore VFP set
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2008): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2008): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 2008): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 2008): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
,I/GBoardtInterface( 2008): onAnimationFinished
,I/GBoardtInterface( 2008): onAnimationFinished
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 285979684269; DSPS: 9511684; Offset : -4309282303
,V/AlarmManager( 1068): RTC_WAKEUP set : Alarm{27ab7b28 type 0 when 1449595853614 com.android.vending} when 1449595853614
,V/SIM_STK ( 1068): Menu title from STK is T-Mobile
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2045): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2045): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2045): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2045): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4925): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4925): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4925): [1] 5.onFinished: Giving up after 6 failures.
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 305981915252; DSPS: 10167117; Offset : -4309279235
,I/[SystemUI]LGPowerUI( 1449): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1449): On Skip Timer : true
,D/WifiController( 1068): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1449): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1449): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1915): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1915): Battery Level Remaining: 100%
D/LEDHandler( 1915): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1449): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3961): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3961): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 325983518733; DSPS: 10822530; Offset : -4309293055
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 345985124871; DSPS: 11477943; Offset : -4309304582
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2045): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2045): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2045): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2045): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1068): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1068): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1068): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1068): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1068): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1068): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ResourcesManager( 1397): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1397): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do add job
D/LgeQuickCoverNotificationData( 1397): add : 2
D/LgeQuickCoverNotificationData( 1397): do add job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
W/GLSActivity( 2045): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2045): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2045): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2045): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2045): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2045): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2045): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
,E/PlayEventLogger( 4925): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4925): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4925): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4925): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager( 1449): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{1159b4aa V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 4925): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1068): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 365986727207; DSPS: 12133355; Offset : -4309289134
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 385988926366; DSPS: 12788787; Offset : -4309287162
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 405990803494; DSPS: 13444209; Offset : -4309302437
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 425992439737; DSPS: 14099622; Offset : -4309283547
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 445994131760; DSPS: 14755038; Offset : -4309300509
,D/PowerManagerServiceEx( 1068): acquireWakeLockInternal: lock=153933912, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1068
,V/AlarmManager( 1068): ELAPSED_WAKEUP set : Alarm{370adea3 type 2 when 358027 com.google.android.gms} when 358027
,D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1068): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1068): releaseWakeLockInternal: lock=153933912 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 465995746178; DSPS: 15410451; Offset : -4309303445
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 485997605339; DSPS: 16065872; Offset : -4309305804
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 505999050487; DSPS: 16721279; Offset : -4309295087
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 526001302303; DSPS: 17376713; Offset : -4309301572
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 546002816774; DSPS: 18032122; Offset : -4309282409
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 566004719162; DSPS: 18687545; Offset : -4309302576
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 586006191134; DSPS: 19342953; Offset : -4309295552
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 606007732532; DSPS: 19998363; Offset : -4309279955
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 626009116326; DSPS: 20653769; Offset : -4309299996
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 646011249080; DSPS: 21309199; Offset : -4309303577
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2045): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2045): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2045): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2045): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1068): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1068): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1068): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1068): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1068): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2045): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2045): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2045): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2045): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2045): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2045): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2045): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4925): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4925): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4925): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4925): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4925): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1068): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{1159b4aa V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 666013033603; DSPS: 21964617; Offset : -4309289048
,I/[SystemUI]LGPowerUI( 1449): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1449): On Skip Timer : true
,D/WifiController( 1068): battery changed pluggedType: 2
,D/LEDHandler( 1915): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1915): Battery Level Remaining: 100%
D/LEDHandler( 1915): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1449): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1449): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1449): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3961): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3961): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 686014540159; DSPS: 22620026; Offset : -4309277722
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 706016134421; DSPS: 23275439; Offset : -4309300970
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 726017663007; DSPS: 23930849; Offset : -4309298003
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 746019050083; DSPS: 24586254; Offset : -4309284426
,I/[SystemUI]LGPowerUI( 1449): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1449): On Skip Timer : true
D/WifiController( 1068): battery changed pluggedType: 2
,D/LEDHandler( 1915): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1915): Battery Level Remaining: 100%
D/LEDHandler( 1915): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1449): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1449): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1449): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3961): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3961): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 766021425649; DSPS: 25241692; Offset : -4309289361
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
,I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 786023216943; DSPS: 25897111; Offset : -4309298474
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 806024597613; DSPS: 26552516; Offset : -4309291095
,D/PowerManagerServiceEx( 1068): acquireWakeLockInternal: lock=153933912, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1068
,V/AlarmManager( 1068): ELAPSED_WAKEUP set : Alarm{25d3eacd type 2 when 757439 com.google.android.gms} when 757439
,D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1068): releaseWakeLockInternal: lock=153933912 [*alarm*], flags=0x0
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1068): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 826026188646; DSPS: 27207928; Offset : -4309286820
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 846028049941; DSPS: 27863349; Offset : -4309287279
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 866029458891; DSPS: 28518755; Offset : -4309282138
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 886031658207; DSPS: 29174187; Offset : -4309280113
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 906033370856; DSPS: 29829604; Offset : -4309306993
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 926034772410; DSPS: 30485010; Offset : -4309309273
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 946036312559; DSPS: 31140420; Offset : -4309295030
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2045): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2045): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2045): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2045): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1068): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1068): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1068): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1068): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1068): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2045): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2045): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2045): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2045): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2045): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2045): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2045): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4925): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4925): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4925): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4925): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4925): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1068): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{1159b4aa V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 966038200676; DSPS: 31795842; Offset : -4309298898
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 986039606397; DSPS: 32451248; Offset : -4309296907
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1006042082015; DSPS: 33106689; Offset : -4309293473
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated(),
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1026043626591; DSPS: 33762100; Offset : -4309305008
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1046045351583; DSPS: 34417516; Offset : -4309289156
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1066046794128; DSPS: 35072923; Offset : -4309280937
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1086048314641; DSPS: 35728333; Offset : -4309286278
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1106049704893; DSPS: 36383739; Offset : -4309299808
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1126051832908; DSPS: 37039169; Offset : -4309308102
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1146053389254; DSPS: 37694579; Offset : -4309277452
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1166054882735; DSPS: 38349988; Offset : -4309279306
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1186056332467; DSPS: 39005396; Offset : -4309294679
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1206058125637; DSPS: 39660815; Offset : -4309301941
,I/UsageStatsService( 1068): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1226059597035; DSPS: 40316223; Offset : -4309295153
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1246061717914; DSPS: 40971652; Offset : -4309280273
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2045): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2045): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2045): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2045): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1068): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1068): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1068): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1068): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1068): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2045): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2045): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2045): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2045): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2045): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2045): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2045): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4925): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4925): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4925): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4925): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4925): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{1159b4aa V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/DSQN    ( 1068): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1266063350093; DSPS: 41627066; Offset : -4309296018
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1286064795086; DSPS: 42282473; Offset : -4309285220
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1306066248359; DSPS: 42937881; Offset : -4309296922
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1326067833403; DSPS: 43593293; Offset : -4309298739
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1346069223240; DSPS: 44248698; Offset : -4309281933
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1366070701305; DSPS: 44904107; Offset : -4309299542
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1386072511453; DSPS: 45559526; Offset : -4309289956
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1406073925769; DSPS: 46214932; Offset : -4309279267
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1426075375605; DSPS: 46870340; Offset : -4309294118
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
,I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1446076896170; DSPS: 47525750; Offset : -4309299746
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1466078275902; DSPS: 48181155; Offset : -4309293252
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1486079713238; DSPS: 48836562; Offset : -4309290295
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1506082141408; DSPS: 49492002; Offset : -4309303609
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1526083551973; DSPS: 50147408; Offset : -4309296775
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1546085004257; DSPS: 50802815; Offset : -4309278842
,I/art     ( 1068): Explicit concurrent mark sweep GC freed 28974(1412KB) AllocSpace objects, 9(528KB) LOS objects, 33% free, 43MB/65MB, paused 2.438ms total 136.313ms
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2045): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2045): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2045): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2045): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1068): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1068): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1068): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1068): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1068): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2045): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2045): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2045): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2045): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2045): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2045): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2045): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4925): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4925): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4925): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4925): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4925): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1068): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{1159b4aa V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1566086864718; DSPS: 51458236; Offset : -4309279928
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1586088243669; DSPS: 52113642; Offset : -4309304577
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1606089691786; DSPS: 52769049; Offset : -4309291020
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1626091891206; DSPS: 53424481; Offset : -4309288970
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1646093288542; DSPS: 54079887; Offset : -4309295260
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1666094748743; DSPS: 54735295; Offset : -4309299929
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1686096290402; DSPS: 55390705; Offset : -4309284124
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1706097697789; DSPS: 56046111; Offset : -4309280518
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1726099285751; DSPS: 56701523; Offset : -4309279574
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1746101586056; DSPS: 57356959; Offset : -4309298501
,I/[SystemUI]LGPowerUI( 1449): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1449): On Skip Timer : true
D/WifiController( 1068): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1449): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1449): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1915): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1915): Battery Level Remaining: 100%
D/LEDHandler( 1915): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1449): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3961): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3961): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1766103077090; DSPS: 58012368; Offset : -4309302829
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1786104532447; DSPS: 58667775; Offset : -4309282033
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1806106035564; DSPS: 59323185; Offset : -4309304378
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1826107549671; DSPS: 59978594; Offset : -4309285736
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1846109011486; DSPS: 60634002; Offset : -4309288817
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1068): Prepared write state in 8ms
,I/GLSUser ( 2045): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2045): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2045): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2045): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2045): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1068): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1068): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1068): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1068): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1068): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2045): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2045): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2045): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2045): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2045): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2045): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2045): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{1159b4aa V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/PlayEventLogger( 4925): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4925): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4925): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4925): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4925): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4925): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1068): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ProcessStatsService( 1068): Pruning old procstats: /data/system/procstats/state-2015-12-07-16-12-49.bin
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1866110695229; DSPS: 61289417; Offset : -4309283698
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1886112421888; DSPS: 61944834; Offset : -4309296410
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1906114630318; DSPS: 62600266; Offset : -4309285271
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1926116437601; DSPS: 63255685; Offset : -4309278526
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1946118204052; DSPS: 63911103; Offset : -4309282146
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1966119661232; DSPS: 64566511; Offset : -4309289759
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 1986122128829; DSPS: 65221952; Offset : -4309294112
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 2006123534446; DSPS: 65877358; Offset : -4309292172
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 2026125381470; DSPS: 66532779; Offset : -4309306642
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
,I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 2046126915889; DSPS: 67188189; Offset : -4309298311
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 2066128565673; DSPS: 67843603; Offset : -4309296553
,D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 2086130717437; DSPS: 68499033; Offset : -4309280917
,I/[SystemUI]TimeTickManager( 1449): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1449): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1449): called onTimeUpdated()
I/[SystemUI]Clock( 1449): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
I/[SystemUI]DateView( 1449): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1449): handleTimeUpdate
D/sensors_hal_Time( 1068): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1068): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1068): tsOffsetIs: Apps: 2106131607638; DSPS: 69154423; Offset : -4309306294
,TIME-OUT KILL (timeout was 1800000ms)
```
