#### Test 5065027873d6a28_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 152759499832; DSPS: 5146419; Offset : -4311557657
,D/AndroidRuntime( 6040): 
D/AndroidRuntime( 6040): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6040): CheckJNI is OFF
D/AndroidRuntime( 6040): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1032): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1949): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1032): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{2a3846d4 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{2a3846d4 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1032): AppWindowTokenEx init.. 
E/GBMv2   (  334): DFP En is all cleared set to be enabled
I/ActivityManager( 1032): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6060 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6040): Shutting down VM
V/ActivityManager( 1032): Display changed displayId=0
D/DSDPConnection( 1853): Display #0 changed.
D/SplitWindowPolicy( 1949): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1949): topRunningActivity=ActivityInfo{3a3265cc co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1949): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1949): topRunningActivity=ActivityInfo{2a41b015 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6060): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6060): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6060): Loading: webviewchromium
,I/LibraryLoader( 6060): Time to load native libraries: 4 ms (timestamps 3495-3499)
I/LibraryLoader( 6060): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6060): Binding Chromium to main looper Looper (main, tid 1) {16b07c81}
I/LibraryLoader( 6060): Expected native library version number "",actual native library version number ""
I/chromium( 6060): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6060): Initializing chromium process, renderers=0
W/art     ( 6060): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6060): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  318): registerClient() client 0xb1427ce0, uid 10311
W/chromium( 6060): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6060): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6060): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d1e0cbe:true
D/BluetoothAdapter( 6060): 1004175654: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6060): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6060): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6060): Build Date: 12/12/14 금
I/Adreno-EGL( 6060): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6060): Remote Branch: 
I/Adreno-EGL( 6060): Local Patches: 
I/Adreno-EGL( 6060): Reconstruct Branch: 
W/chromium( 6060): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6060): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6060): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6060): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6060): CordovaWebView is running on device made by: LGE
W/art     ( 6060): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6060): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6060): Render dirty regions requested: true
I/OpenGLRenderer( 6060): Initialized EGL, version 1.4
D/OpenGLRenderer( 6060): Enabling debug mode 0
D/Atlas   ( 6060): Validating map...
D/SplitWindow( 1032): check instance of lgWin Window{c410288 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6060): LgDataFeature() Constructor: none
D/LgDataFeature( 6060): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1451): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1451): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1451):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1451): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17d2fcb6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1032): Displayed com.test.thalitest/.MainActivity: +620ms (total +698ms)
I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{3b82f07d u0 com.test.thalitest/.MainActivity t4} time:163964
I/Timeline( 6060): Timeline: Activity_idle id: android.os.BinderProxy@2c5b7fd6 time:163965
D/JsMessageQueue( 6060): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6060): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6060): 
D/jxcore_app_log( 6060): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435069184
D/JX-Cordova( 6060): jxcore cordova android initializing
,E/GBMv2   (  334): DFP En is all cleared set to be enabled
E/GBMv2   (  334): Set value is all cleared set the max
I/GBMv2   (  334): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6060): Initializing JXcore engine
W/jxcore-log( 6060): JXcore engine is ready
,W/jxcore-log( 6060): Starting JXcore engine
W/.test.thalitest( 6060): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[7416]" dev="sockfs" ino=7416 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 6060): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6060): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[7612]" dev="sockfs" ino=7612 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6060): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6060): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[30363]" dev="sockfs" ino=30363 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6060): Platform android
W/jxcore-log( 6060): 
W/jxcore-log( 6060): Process ARCH arm
W/jxcore-log( 6060): 
,I/jxcore-log( 6060): JXcore Cordova bridge is ready!
I/jxcore-log( 6060): 
W/jxcore-log( 6060): JXcore engine is started
,I/chromium( 6060): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6060): 
E/jxcore  ( 6060): Error!: missing ) after argument list
E/jxcore  ( 6060): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6060): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager( 1032): Killing 4458:com.google.android.talk/u0a72 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10072/pid_4458/cgroup.procs: No such file or directory
,W/PluginManager( 6060): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 47ms. Plugin should use CordovaInterface.getThreadPool().
,E/GBMv2   (  334): DFP En is all cleared set to be enabled
,D/SplitWindowPolicy( 1949): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1949): topRunningActivity=ActivityInfo{6dc8f2a co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1949): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1949): topRunningActivity=ActivityInfo{403f11b co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
W/ScreenOrientationListener( 6060): Removing an inexistent observer!
I/[LGHome]EVENT( 2072): [Launcher.java:5338:onStart()]onStart
,I/[LGHome]EVENT( 2072): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2072): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2072): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/InputDispatcher( 1032): Window went away: Window{c410288 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/ActionManagerService( 1913): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2713): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2072): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2072): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2072): [Launcher.java:1056:onResume()]onResume end
,I/ActivityManager( 1032): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6141 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2072): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1913): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2713): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2072): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 2713): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2072): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2072): , create_time: 1430558575574
I/GBoardWebViewUtils( 2072): , expire_time: 0
I/GBoardWebViewUtils( 2072): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2072): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2072): , display: false
I/GBoardWebViewUtils( 2072): , animation: false }
I/GBoardWebViewUtils( 2072): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2072): , create_time: 1430558575600
I/GBoardWebViewUtils( 2072): , expire_time: 0
I/GBoardWebViewUtils( 2072): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2072): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2072): , display: false
I/GBoardWebViewUtils( 2072): , animation: false }
I/GBoardWebViewUtils( 2072): checkExpiredAndRemoveCard() card: GBoardCard = { id: new_feature_1111111111111_1449584869051
I/GBoardWebViewUtils( 2072): , create_time: 1449584869233
I/GBoardWebViewUtils( 2072): , expire_time: 0
I/GBoardWebViewUtils( 2072): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2072): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2072): , display: false
I/GBoardWebViewUtils( 2072): , animation: false }
,D/WallpaperManager( 2072): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
D/PhoneStatusBar( 1451): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1451): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1451):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1451): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17d2fcb6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[LGHome]GBoardWebView( 2072): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/art     ( 6141): Almond Protected OAT
,D/WeatherApplication( 6141): removeAccount
,D/WeatherApplication( 6141): Account.length = 0
E/WeatherApplication( 6141): OPERATOR:OPEN
D/WeatherAncestor( 6141): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 3:4:43
D/Weather.Utils( 6141): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6141): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6141): 2 : This is isUpdating : false
D/Weather.Utils( 6141): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6141): 2 : All the weather widget is gone.
D/WeatherAncestor( 6141): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 3:4:43
I/ActivityManager( 1032): Killing 5798:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10008/pid_5798/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2072): [Launcher.java:5349:onStop()]onStop
I/[LGHome]Launcher.Model( 2072): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{20d7d42a u0 com.lge.launcher2/.Launcher t3} time:167167
,I/[LGHome]Launcher.Model( 2072): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2072): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2072): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2072): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2072): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2576): onStartCommand(). Type : 8
D/[Concierge]Service( 2576): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2576): Update widget ID : 11
D/[Concierge]WidgetView( 2072): change position of spinner
,I/[Concierge]WidgetView( 2072): initWebView(). Time : 1449626683345
D/[Concierge]Service( 2576): onStartCommand(). Type : 0
I/[Concierge]WebView( 2072): Return exist ConciergeWebView. Reuse : 757433695
D/[Concierge]WidgetView( 2072): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2072): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2072): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@30ce9504
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2072): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2072): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2072): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2072): Widget kill message received. Destory myself. My : 1449626544375, New one : 1449626683345
D/[Concierge]WidgetView( 2072): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2072): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2072): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2072): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2072): Timeline: Activity_idle id: android.os.BinderProxy@30fff296 time:167443
,I/chromium( 2072): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2072): onReloaded()
,I/GBoardWebViewClient( 2072): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2713): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2713): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/ActionManagerService( 1913): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2713): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2713): onEvent() : ACTION_BOARD_ENABLED
,I/ActivityManager( 1032): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6176 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/ActionManagerService( 1913): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2713): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2713): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2713): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2713): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2713): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2072): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2072): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2072): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2072): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,D/GBoardUriUtils( 2072): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature2.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2072): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/PromotionCard/NewFeatureCard/newfeature2.html?id=new_feature_1111111111111_1449584869051&desc=[@string/gboard_pc_newfeature_desc]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,V/FormManager( 6176): BoardCategory : com.lge.intent.category.gboard.MYWELLNESS, true
,E/GBMv2   (  334): DFP En is all cleared set to be enabled
E/GBMv2   (  334): Set value is all cleared set the max
I/GBMv2   (  334): DFP Enabled. Ignore VFP set
,I/ActivityManager( 1032): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6203 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/FormManager( 6176): Network unavailable.
,W/FormManager( 6176): Network not available. Please check & try again.
V/FormManager( 6176): Network unavailable.
I/ActivityManager( 1032): Killing 5457:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10011/pid_5457/cgroup.procs: No such file or directory
,E/ActivityThread( 6203): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6203): No ProfileInfo entries
I/LG Account v2.2( 6203): isEnabled: false
I/Feature ( 6203): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6203): [Lifetracker]Country: EU
I/Feature ( 6203): [Lifetracker]Operator: OPEN
I/Feature ( 6203): [Lifetracker]Ranking support: false
I/Feature ( 6203): [Lifetracker]Comfort support: false
I/Feature ( 6203): [Lifetracker]Accessory: true
I/Feature ( 6203): [Lifetracker]Health device: true
I/Feature ( 6203): [Lifetracker]Extra Pedometer: false
I/Feature ( 6203): [Lifetracker]Blood glucose device: false
I/Feature ( 6203): [Lifetracker]Device Number: 3
D/CoreEventReceiver( 6203): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
,I/GBoardStateUtil( 6203): [GBoardStateUtil] isEnableLGHealthofGBoard : true
I/CoreEventReceiver( 6203): gboardCategory : com.lge.intent.category.gboard.MYWELLNESS, gboardState : true
,I/ActivityManager( 1032): Killing 5483:com.android.contacts/u0a19 (adj 15): empty #17
,I/LIA_Informant_LogCore( 2713): LIA Log setTagPrefix - prefix : LIA_Informant_
,I/LIA_Informant_BoardCondition( 2713): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
,W/libprocessgroup( 1032): failed to open /acct/uid_10019/pid_5483/cgroup.procs: No such file or directory
I/LIA_MrGDBLogger_LogCore( 2713): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2713): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
I/LIA_S4URecommender_LogCore( 2713): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_BoardCondition( 2713): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.MYWELLNESS) state(true)
,I/GBoardtInterface( 2072): exportHTML()
,D/CoreEventReceiver( 6203): [onReceive] Action=com.lge.mrg.service.BOARD_STATE_CHANGED
V/FormManager( 6176): BoardCategory : com.lge.intent.category.gboard.DOYOUKNOW, true
I/GBoardStateUtil( 6203): [GBoardStateUtil] isEnableLGHealthofGBoard : true
I/CoreEventReceiver( 6203): gboardCategory : com.lge.intent.category.gboard.DOYOUKNOW, gboardState : true
,I/LIA_Informant_LogCore( 2713): LIA Log setTagPrefix - prefix : LIA_Informant_
I/LIA_Informant_BoardCondition( 2713): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/LIA_Informant_BoardStateUtil( 2713): defaultHomePackage : com.lge.launcher2
D/LIA_Informant_TaskActivator( 2713): DefaultHomeCondition is satisfied
V/FormManager( 6176): Network unavailable.
W/FormManager( 6176): Network not available. Please check & try again.
V/FormManager( 6176): Network unavailable.
,I/LIA_Informant_BoardStateUtil( 2713): isEnabledConciergeBoard() : count > 0 - true
D/LIA_Informant_TaskActivator( 2713): BoardCondition is satisfied
W/LIA_Informant_TaskActivator( 2713): setActivation() : Informant Task - ACTIVATION
D/LIA_Informant_LGIntelligentAgent( 2713): activateLIAService : Informant / true
I/LIA_Informant_LIATaskLoader( 2713): getTaskSdkClassName : com.lge.ia.LIAInformant
I/GBoardtInterface( 2072): exportHTML()
D/LIA_Informant_LIATaskLoader( 2713): classLoad - TargetClass : com.lge.ia.LIAInformant
I/LIA_Informant_LIATaskLoader( 2713): createLIAService - Success
I/LIA_Informant_LGIntelligentAgent( 2713): activateLIAService : startService success. (You may need to check whether its property has changed or not!)
,D/LIA_Informant_LIARemoteService( 2713): onStartCommand() : LIARemoteService started! - (Id :5), Intent { act=com.lge.ia.task.informant pkg=com.lge.ia.task.informant (has extras) }
I/LIA_Informant_InformantService( 2713): isNowInActivationCondition()
I/LIA_Informant_BoardStateUtil( 2713): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_ActivationConditionHandler( 2713): ActivationConditionHandler : LGHome condition is true
I/LIA_Informant_BoardStateUtil( 2713): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ActivationConditionHandler( 2713): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 2713): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
I/LIA_Informant_InformantService( 2713): getTaskPropertiesAtFirstStarting()
D/LIA_Informant_LIARemoteService( 2713): --> LIA task activation intent from com.lge.ia.task.informant for Informant(activation: true)
D/LIA_Informant_LIARemoteService( 2713): updateTaskProperty() : 
I/LIA_Informant_LIARemoteService( 2713): --> LIA task activation intent from com.lge.ia.task.informant, but it's same as the current setting or couldn't chagne it so just passed !! (Informant activation : true)
I/LIA_MrGDBLogger_LogCore( 2713): [dreamwood]LIA Log setTagPrefix - prefix : LIA_MrGDBLogger_
I/LIA_MrGDBLogger_BoardCondition( 2713): [dreamwood]onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/LIA_S4URecommender_LogCore( 2713): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_BoardCondition( 2713): onReceive(com.lge.mrg.service.BOARD_STATE_CHANGED): category(com.lge.intent.category.gboard.DOYOUKNOW) state(true)
I/GBoardtInterface( 2072): exportHTML()
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2072): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2072): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 2072): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 2072): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
,I/GBoardtInterface( 2072): onAnimationFinished
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 170262026710; DSPS: 5719943; Offset : -4311592928
,I/GBoardtInterface( 2072): onAnimationFinished
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{227e1db8 type 0 when 1449626686364 com.android.vending} when 1449626686364
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 24171(1128KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.814ms total 94.923ms
,I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4905): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4905): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4905): [1] 5.onFinished: Scheduling replication attempt 3.
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 190264016493; DSPS: 6375368; Offset : -4311588012
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 210265639611; DSPS: 7030781; Offset : -4311582221
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=358247603, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{c3229da type 2 when 178984 com.google.android.gms} when 178984
V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{319064e8 type 0 when 1449626711687 com.android.vending} when 1449626711687
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{ca9d701 type 2 when 209978 com.google.android.gms} when 209978
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=358247603 [*alarm*], flags=0x0
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager( 1032): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6262 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6262): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,D/LgDataFeature( 6262): LgDataFeature() Constructor: none
D/LgDataFeature( 6262): LgDataFeature() Constructor Done, null
,I/art     ( 2116): Explicit concurrent mark sweep GC freed 22643(1272KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 967us total 42.791ms
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4905): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4905): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4905): [1] 5.onFinished: Scheduling replication attempt 4.
,I/Babel   ( 6262): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6262): MmsConfig.loadMmsSettings
I/Babel   ( 6262): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6262): MmsConfig.loadFromDatabase
,W/Settings( 6262): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 6262): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6262): MmsConfig.loadFromResources
E/Babel   ( 6262): canonicalizeMccMnc: invalid mccmnc nullnull
W/AudioCapabilities( 6262): Unsupported mime audio/evrc
I/Babel   ( 6262): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/AudioCapabilities( 6262): Unsupported mime audio/qcelp
W/VideoCapabilities( 6262): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6262): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6262): Unsupported mime audio/qcelp
W/AudioCapabilities( 6262): Unsupported mime audio/evrc
W/VideoCapabilities( 6262): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6262): Unsupported mime video/divx
W/VideoCapabilities( 6262): Unsupported mime video/divx311
W/VideoCapabilities( 6262): Unsupported mime video/divx4
I/ActivityManager( 1032): Killing 5818:com.lge.email/u0a23 (adj 15): empty #17
W/VideoCapabilities( 6262): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6262): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6262): Unsupported mime audio/eac3
W/AudioCapabilities( 6262): Unsupported mime audio/ac3
W/AudioCapabilities( 6262): Unsupported mime audio/g726
W/AudioCapabilities( 6262): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6262): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6262): Unsupported mime audio/adpcm
W/VideoCapabilities( 6262): Unsupported mime video/theora
W/VideoCapabilities( 6262): Unsupported mime video/mjpg
W/libprocessgroup( 1032): failed to open /acct/uid_10023/pid_5818/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 230267331114; DSPS: 7686197; Offset : -4311599911
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{32eed4ad type 2 when 238568 android} when 238568
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{133b6373 type 0 when 1449626757446 com.android.vending} when 1449626757446
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4905): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4905): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4905): [1] 5.onFinished: Scheduling replication attempt 5.
I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1451): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1451): On Skip Timer : true
,D/WifiController( 1032): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1451): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1949): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1949): Battery Level Remaining: 100%
D/LEDHandler( 1949): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 250268975481; DSPS: 8341610; Offset : -4311572741
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 270271048339; DSPS: 8997039; Offset : -4311605960
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=358247603, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{87c9992 type 0 when 1449626778411 com.android.vending} when 1449626778411
,D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=358247603 [*alarm*], flags=0x0
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4905): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4905): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4905): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 290272690154; DSPS: 9652452; Offset : -4311581369
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 310274218844; DSPS: 10307862; Offset : -4311578427
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 330275676336; DSPS: 10963270; Offset : -4311585701
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 350277231225; DSPS: 11618681; Offset : -4311587573
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GLSActivity( 2116): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2116): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2116): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2116): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2116): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2116): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2116): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{9dc072f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/PlayEventLogger( 4905): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4905): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4905): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4905): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4905): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 370278830488; DSPS: 12274093; Offset : -4311575120
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 390283492407; DSPS: 12929606; Offset : -4311582417
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 410288209796; DSPS: 13585121; Offset : -4311595331
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 430290164840; DSPS: 14240545; Offset : -4311593203
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=358247603, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{24e2089f type 2 when 422777 com.google.android.gms} when 422777
,D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=358247603 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 450291671239; DSPS: 14895954; Offset : -4311582400
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 470293122273; DSPS: 15551362; Offset : -4311596002
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 490294612109; DSPS: 16206771; Offset : -4311601474
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 510296107362; DSPS: 16862180; Offset : -4311601791
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 530297494749; DSPS: 17517585; Offset : -4311587590
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 550299216616; DSPS: 18173001; Offset : -4311574709
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 570300782443; DSPS: 18828413; Offset : -4311595769
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 590302410873; DSPS: 19483826; Offset : -4311584692
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
,I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 610303928676; DSPS: 20139236; Offset : -4311592820
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 630305415493; DSPS: 20794645; Offset : -4311601365
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 650307023506; DSPS: 21450057; Offset : -4311580266
,I/ActivityManager( 1032): Killing 5507:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10027/pid_5507/cgroup.procs: No such file or directory
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GLSActivity( 2116): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2116): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2116): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2116): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2116): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2116): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2116): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4905): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4905): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4905): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4905): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4905): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{9dc072f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 670308569800; DSPS: 22105468; Offset : -4311590290
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 690310386356; DSPS: 22760887; Offset : -4311574375
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 710311787232; DSPS: 23416293; Offset : -4311577335
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 730313000975; DSPS: 24071693; Offset : -4311584320
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 750314502739; DSPS: 24727102; Offset : -4311577892
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 770315447211; DSPS: 25382493; Offset : -4311579282
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
,I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 790316714859; DSPS: 26037895; Offset : -4311591237
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 810318230840; DSPS: 26693304; Offset : -4311572987
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 830331527864; DSPS: 27349100; Offset : -4311581445
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 850333020513; DSPS: 28004509; Offset : -4311584287
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 870334521599; DSPS: 28659918; Offset : -4311578511
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 890335918675; DSPS: 29315324; Offset : -4311585191
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=358247603, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{40a0c69 type 2 when 840519 com.google.android.gms} when 840519
,D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=358247603 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 910337425178; DSPS: 29970733; Offset : -4311574180
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 930338930378; DSPS: 30626143; Offset : -4311594780
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 950340979642; DSPS: 31281570; Offset : -4311590142
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GLSActivity( 2116): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2116): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2116): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2116): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2116): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2116): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2116): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4905): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4905): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4905): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4905): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4905): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{9dc072f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 970342849113; DSPS: 31936991; Offset : -4311582400
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 990344360407; DSPS: 32592401; Offset : -4311596802
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1010345760817; DSPS: 33247807; Offset : -4311600280
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1030347487475; DSPS: 33903223; Offset : -4311582683
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1050349251062; DSPS: 34558641; Offset : -4311589117
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1070351807565; DSPS: 35214085; Offset : -4311596011
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1090353570578; DSPS: 35869503; Offset : -4311603071
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1110355077549; DSPS: 36524912; Offset : -4311591460
,I/[SystemUI]LGPowerUI( 1451): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1451): On Skip Timer : true
,D/WifiController( 1032): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1451): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1949): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1949): Battery Level Remaining: 100%
D/LEDHandler( 1949): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1130356526812; DSPS: 37180319; Offset : -4311576289
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1150358029982; DSPS: 37835729; Offset : -4311599259
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1170359531641; DSPS: 38491138; Offset : -4311593039
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1190361858248; DSPS: 39146574; Offset : -4311585352
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1210363342824; DSPS: 39801983; Offset : -4311596423
,I/UsageStatsService( 1032): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1230364867920; DSPS: 40457393; Offset : -4311596997
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1250366546193; DSPS: 41112808; Offset : -4311597270
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GLSActivity( 2116): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2116): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2116): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2116): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2116): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2116): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2116): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4905): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4905): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4905): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4905): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4905): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{9dc072f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1270368106498; DSPS: 41768219; Offset : -4311593309
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1290369856751; DSPS: 42423636; Offset : -4311582714
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1310372248411; DSPS: 43079075; Offset : -4311601917
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1330374031112; DSPS: 43734493; Offset : -4311589287
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1350375548447; DSPS: 44389903; Offset : -4311597858
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1370376960730; DSPS: 45045309; Offset : -4311589357
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1390378444109; DSPS: 45700718; Offset : -4311601314
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1410380829570; DSPS: 46356156; Offset : -4311596406
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1430382255761; DSPS: 47011563; Offset : -4311604306
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1450383991743; DSPS: 47666979; Offset : -4311577388
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1470385495798; DSPS: 48322389; Offset : -4311599159
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1490387096466; DSPS: 48977801; Offset : -4311585300
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1510388580365; DSPS: 49633210; Offset : -4311596894
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1530390747910; DSPS: 50288641; Offset : -4311596148
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1550392495507; DSPS: 50944058; Offset : -4311588054
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1032): Explicit concurrent mark sweep GC freed 28831(1313KB) AllocSpace objects, 8(640KB) LOS objects, 33% free, 44MB/66MB, paused 1.687ms total 125.903ms
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2116): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2116): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2116): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2116): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2116): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2116): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2116): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
E/PlayEventLogger( 4905): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4905): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4905): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4905): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4905): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
,D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{9dc072f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1570394282426; DSPS: 51599477; Offset : -4311601620
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1590396053303; DSPS: 52254895; Offset : -4311600710
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1610397452775; DSPS: 52910300; Offset : -4311574582
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1630399319122; DSPS: 53565722; Offset : -4311600402
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1650401539896; DSPS: 54221154; Offset : -4311576815
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1670403134107; DSPS: 54876567; Offset : -4311599984
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1690404613213; DSPS: 55531975; Offset : -4311585826
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1710406115497; DSPS: 56187384; Offset : -4311578956
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1730407523198; DSPS: 56842790; Offset : -4311575063
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1451): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1451): On Skip Timer : true
,D/WifiController( 1032): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1451): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1949): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1949): Battery Level Remaining: 100%
D/LEDHandler( 1949): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1750409059857; DSPS: 57498201; Offset : -4311594748
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1770411512142; DSPS: 58153641; Offset : -4311583817
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1790412984373; DSPS: 58809049; Offset : -4311576457
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1810414560824; DSPS: 59464461; Offset : -4311586867
,I/[SystemUI]LGPowerUI( 1451): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1451): On Skip Timer : true
,D/WifiController( 1032): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1451): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1451): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1949): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1949): Battery Level Remaining: 100%
D/LEDHandler( 1949): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1830416134931; DSPS: 60119873; Offset : -4311599701
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1850417798985; DSPS: 60775287; Offset : -4311583595
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1032): Prepared write state in 9ms
,I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GLSActivity( 2116): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2116): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2116): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2116): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2116): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2116): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2116): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{9dc072f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/PlayEventLogger( 4905): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4905): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4905): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4905): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4905): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 4905): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ProcessStatsService( 1032): Pruning old procstats: /data/system/procstats/state-2015-12-08-08-05-36.bin
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1870419436738; DSPS: 61430701; Offset : -4311593870
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1890421648763; DSPS: 62086133; Offset : -4311579032
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1910423383442; DSPS: 62741550; Offset : -4311583725
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1930424930518; DSPS: 63396961; Offset : -4311593254
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1950431211708; DSPS: 64052527; Offset : -4311598633
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1970432934044; DSPS: 64707943; Offset : -4311585256
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1990434486380; DSPS: 65363354; Offset : -4311589238
,TIME-OUT KILL (timeout was 1800000ms)
```
