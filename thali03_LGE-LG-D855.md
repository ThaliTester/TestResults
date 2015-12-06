#### Test 50242285576d0b0_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/UEI.SmartControl( 5848): Internal timer expired: 1
D/UEI.SmartControl( 5848): unbind internal service
,D/serial_port( 5848): close(fd = 25)
I/UEI.SmartControl( 5848): Serial port is closed.
D/AndroidRuntime( 5942): 
D/AndroidRuntime( 5942): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5942): CheckJNI is OFF
D/AndroidRuntime( 5942): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1030): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1956): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1030): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{f354660 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{f354660 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1030): AppWindowTokenEx init.. 
E/GBMv2   (  348): DFP En is all cleared set to be enabled
I/ActivityManager( 1030): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5957 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5942): Shutting down VM
V/ActivityManager( 1030): Display changed displayId=0
D/DSDPConnection( 1869): Display #0 changed.
D/SplitWindowPolicy( 1956): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1956): topRunningActivity=ActivityInfo{9a59b8f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1956): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1956): topRunningActivity=ActivityInfo{3082fe1c co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 5957): convertTheme. context->name=com.example.hello themeResourceId=16973833
,I/WebViewFactory( 5957): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 5957): Loading: webviewchromium
I/LibraryLoader( 5957): Time to load native libraries: 3 ms (timestamps 4965-4968)
I/LibraryLoader( 5957): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5957): Binding Chromium to main looper Looper (main, tid 1) {db851b8}
I/LibraryLoader( 5957): Expected native library version number "",actual native library version number ""
I/chromium( 5957): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5957): Initializing chromium process, renderers=0
W/art     ( 5957): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5957): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  328): registerClient() client 0xb146c080, uid 10318
W/chromium( 5957): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5957): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5957): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25b2fea:true
D/BluetoothAdapter( 5957): 749800337: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 5957): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5957): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5957): Build Date: 12/12/14 금
I/Adreno-EGL( 5957): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5957): Remote Branch: 
I/Adreno-EGL( 5957): Local Patches: 
I/Adreno-EGL( 5957): Reconstruct Branch: 
W/chromium( 5957): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 5957): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5957): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5957): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5957): CordovaWebView is running on device made by: LGE
W/art     ( 5957): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5957): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5957): Render dirty regions requested: true
I/OpenGLRenderer( 5957): Initialized EGL, version 1.4
D/OpenGLRenderer( 5957): Enabling debug mode 0
D/Atlas   ( 5957): Validating map...
D/SplitWindow( 1030): check instance of lgWin Window{17f03754 u0 com.example.hello/com.example.hello.MainActivity}
D/LgDataFeature( 5957): LgDataFeature() Constructor: none
D/LgDataFeature( 5957): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@16a3e617,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1460): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1460): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1460):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1460): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 5957): Timeline: Activity_idle id: android.os.BinderProxy@329afb01 time:75400
I/ActivityManager( 1030): Displayed com.example.hello/.MainActivity: +598ms (total +695ms)
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{3606719 u0 com.example.hello/.MainActivity t4} time:75402
I/chromium( 5957): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 5957): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 5957): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 5957): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5957): 
I/chromium( 5957): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5957): 
D/jxcore_app_log( 5957): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435345664
D/JX-Cordova( 5957): jxcore cordova android initializing
W/jxcore-log( 5957): Initializing JXcore engine
W/jxcore-log( 5957): JXcore engine is ready
W/jxcore-log( 5957): Starting JXcore engine
E/GBMv2   (  348): DFP En is all cleared set to be enabled
E/GBMv2   (  348): Set value is all cleared set the max
I/GBMv2   (  348): DFP Enabled. Ignore VFP set
W/m.example.hello( 5957): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[7471]" dev="sockfs" ino=7471 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 5957): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 5957): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7521]" dev="sockfs" ino=7521 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 5957): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/m.example.hello( 5957): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[26564]" dev="sockfs" ino=26564 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 5957): Platform android
W/jxcore-log( 5957): 
W/jxcore-log( 5957): Process ARCH arm
W/jxcore-log( 5957): 
,I/jxcore-log( 5957): JXcore Cordova bridge is ready!
I/jxcore-log( 5957): 
,W/jxcore-log( 5957): JXcore engine is started
,E/jxcore-log( 5957): >> LGE-LG-D855
E/jxcore-log( 5957): 
I/jxcore-log( 5957): Total memory 2995761152
I/jxcore-log( 5957): 
I/jxcore-log( 5957): Free memory 639328256
I/jxcore-log( 5957): 
I/jxcore-log( 5957): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5957): 
I/jxcore-log( 5957): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5957): 
,I/jxcore-log( 5957): userPath [ 'www' ]
I/jxcore-log( 5957): 
I/jxcore-log( 5957): Size 1440 2392
I/jxcore-log( 5957): 
I/jxcore-log( 5957): Screen Brightness 50
I/jxcore-log( 5957): 
E/jxcore-log( 5957): Dummy Error Log.
E/jxcore-log( 5957): 
,I/jxcore-log( 5957): getBuffer is called!!!!
I/jxcore-log( 5957): 
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 77278264608; DSPS: 2673588; Offset : -4322437461
,I/ActivityManager( 1030): Killing 5519:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_5519/cgroup.procs: No such file or directory
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1030): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService( 1030): Message: 2
D/WifiService( 1030): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1030): setWifiEnabled: false pid=5957, uid=10318, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1030): setWifiEnabled: false pid=5957, uid=10318
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 5957): ****TEST TOOK:  5069  ms ****
I/jxcore-log( 5957): 
I/jxcore-log( 5957): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5957): 
D/InitAlarmsService( 4822): Clearing and rescheduling alarms.
,I/ActivityManager( 1030): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6051 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 6051): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6051): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@27eeb4cc
,D/CalendarProvider2( 6051): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6051): Created com.android.providers.calendar.CalendarAlarmManager@2cb10b91(com.android.providers.calendar.CalendarProvider2@27eeb4cc)
D/CalendarProvider2( 6051): Scheduling check of next Alarm
D/CalendarProvider2( 6051): SCHEDULE_ALARM_REMOVE
,I/ActivityManager( 1030): Killing 4822:com.android.calendar/u0a13 (adj 15): empty #17
D/AndroidRuntime( 6060): 
D/AndroidRuntime( 6060): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6060): CheckJNI is OFF
W/libprocessgroup( 1030): failed to open /acct/uid_10013/pid_4822/cgroup.procs: No such file or directory
,D/AndroidRuntime( 6060): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1030): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1030): Killing 5957:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/WindowState( 1030): WIN DEATH: Window{17f03754 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1030): Client connection lost with reason: 4
D/InputDispatcher( 1030): Window went away: Window{17f03754 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings( 1030): Skipping PackageSetting{18dd0dcf com.test.thalitest/10311} due to missing metadata
,I/ActivityManager( 1030):   Force finishing activity ActivityRecord{3606719 u0 com.example.hello/.MainActivity t4}
,E/GBMv2   (  348): DFP En is all cleared set to be enabled
W/ActivityManager( 1030): Spurious death for ProcessRecord{3918eabb 5957:com.example.hello/u0a318}, curProc for 5957: null
I/ActivityManager( 1030): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1030):   Force finishing activity ActivityRecord{3606719 u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager( 1030): Duplicate finish request for ActivityRecord{3606719 u0 com.example.hello/.MainActivity t4 f}
,I/[LGHome]EVENT( 2084): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1956): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1956): topRunningActivity=ActivityInfo{36daea25 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2084): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1956): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1956): topRunningActivity=ActivityInfo{c2b27fa co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]EVENT( 2084): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2084): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/KeyguardModel( 1460): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4200): Explicit concurrent mark sweep GC freed 15005(861KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 696us total 68.488ms
,W/GeofencerStateMachine( 1834): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 2028): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
,D/LIA_MrGDBLogger_PackageInfoDetector( 2728): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
D/ActionManagerService( 1920): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2084): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,D/LIA_Informant_ActionManagerMessageHandler( 2728): handleMessage: what(1000) actionID(0x1000003)
I/[SystemUI]QSlideListController( 1460): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 2084): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2084): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2084): [Launcher.java:1114:onPause()]onPause
D/PostponalbeReceiver( 5130): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,D/KeyguardModel( 1460): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1460): createShortcutInfo...
D/ActionManagerService( 1920): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2728): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2084): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,V/BoardContentProvider( 2728): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/KeyguardModel( 1460): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1460): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1460): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1460): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/GBoardWebViewUtils( 2084): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2084): , create_time: 1430558575574
I/GBoardWebViewUtils( 2084): , expire_time: 0
I/GBoardWebViewUtils( 2084): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2084): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2084): , display: false
I/GBoardWebViewUtils( 2084): , animation: false }
I/GBoardWebViewUtils( 2084): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2084): , create_time: 1430558575600
I/GBoardWebViewUtils( 2084): , expire_time: 0
I/GBoardWebViewUtils( 2084): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2084): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2084): , display: false
I/GBoardWebViewUtils( 2084): , animation: false }
I/GBoardWebViewUtils( 2084): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1449156806130
I/GBoardWebViewUtils( 2084): , create_time: 1449156807049
I/GBoardWebViewUtils( 2084): , expire_time: 0
I/GBoardWebViewUtils( 2084): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2084): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2084): , display: false
I/GBoardWebViewUtils( 2084): , animation: false }
W/ResourcesManager( 1460): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1460): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1460): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1460): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1460): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1460): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/WallpaperManager( 2084): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
W/System.err( 4152): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 4152): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4152): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4152): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4152): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4152): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4152): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4152): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4152): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4152): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@16a3e617,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1460): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1460): createShortcutInfo...
,I/[LGHome]EVENT( 2084): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
W/ResourcesManager( 1460): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1460): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]GBoardWebView( 2084): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourceType( 1460): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1460): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/SplitUIManager( 1886): split_name #11 / not available #0
D/SplitUIService( 1886): removed split : 
D/KeyguardModel( 1460): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1460): createShortcutInfo...
W/ResourcesManager( 1460): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1460): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1460): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1460): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1460): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1460): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1460): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1460): createShortcutInfo...
D/KeyguardModel( 1460): handleShortcutListChanged...
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 12390(977KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.115ms total 192.346ms
D/KeyguardModel( 1460): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1460): createShortcutInfo...
D/AppUp4:PreloadHelper( 5474): added Exclude : com.example.hello
I/art     ( 1030): WaitForGcToComplete blocked for 109.799ms for cause Explicit
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
D/KeyguardModel( 1460): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1460): createShortcutInfo...
,D/SplitUIManager( 1886): split_name #11 / not available #0
I/SplitUIService( 1886): split app #11
W/ResourceType( 1460): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1460): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1460): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1460): createShortcutInfo...
W/ResourceType( 1460): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1460): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/VoicemailCleanupService( 2196): Cleaning up data for package: com.example.hello
D/KeyguardModel( 1460): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1460): createShortcutInfo...
W/ResourceType( 1460): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1460): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1460): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1460): createShortcutInfo...
,I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6123 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/KeyguardModel( 1460): handleShortcutListChanged...
I/[LGHome]EVENT( 2084): [Launcher.java:5349:onStop()]onStop
D/administrator( 1030): Handling package changes for user 0
,W/ResourcesManager( 6123): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6123): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6123): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6123): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,I/[LGHome]Launcher.Model( 2084): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2084): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2084): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2084): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2084): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2084): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/[LGHome]Launcher.Model( 2084): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2084): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]Launcher( 2084): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2084): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/NotificationService( 1030): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1030): Receieved: android.intent.action.PACKAGE_REMOVED
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{bf9e325 u0 com.lge.launcher2/.Launcher t3} time:82672
,I/LGEmail ( 6123): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/[LGHome]EVENT( 2084): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2084): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2084): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/TaskPersister( 1030): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1460): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1460): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1460):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1460): , Keyguard show=false, IME shown=false, Panel expanded=false
I/art     ( 1030): Explicit concurrent mark sweep GC freed 5852(299KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.336ms total 201.915ms
D/LGEmail ( 6123): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
I/[Concierge]WidgetView( 2084): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/[Concierge]Service( 2608): onStartCommand(). Type : 8
D/[Concierge]Service( 2608): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2608): Update widget ID : 11
D/[Concierge]WidgetView( 2084): change position of spinner
I/[Concierge]WidgetView( 2084): initWebView(). Time : 1449411021628
D/[Concierge]Service( 2608): onStartCommand(). Type : 0
,W/ResourceType( 6123): No package identifier when getting value for resource number 0x00000000
,I/[Concierge]WebView( 2084): Return exist ConciergeWebView. Reuse : 416061388
D/[Concierge]WidgetView( 2084): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2084): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2084): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@119eab66
I/[LGHome]EVENT( 2084): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2084): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2084): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2084): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2084): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2084): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,D/AndroidRuntime( 6060): Shutting down VM
W/[Concierge]WidgetView( 2084): Widget kill message received. Destory myself. My : 1449410966859, New one : 1449411021628
D/[Concierge]WidgetView( 2084): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2084): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/[LGHome]Launcher( 2084): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2084): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2084): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2084): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
D/LgDataFeature( 6123): LgDataFeature() Constructor: none
D/LgDataFeature( 6123): LgDataFeature() Constructor Done, null
I/[LGHome]EVENT( 2084): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2084): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2084): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2084): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/CalendarProvider2( 6051): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6051): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 1030): Killing 5571:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2084): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
E/[LgeWidgetLib]LgeAppWidgetHostView( 2084): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 2084): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2084): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2084): Timeline: Activity_idle id: android.os.BinderProxy@3f9021cb time:82857
,W/libprocessgroup( 1030): failed to open /acct/uid_10061/pid_5571/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 2084): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/PackageChangeReceiver( 6123): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager( 1030): Killing 5705:com.lge.eula/1000 (adj 15): empty #17
,I/chromium( 2084): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,D/LIA_Service_NativeEventReceiver( 2028): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
,I/LIA_Service_PlatformUtil( 2028): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5705/cgroup.procs: No such file or directory
D/LIA_Service_LIAService( 2028): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,D/PostponalbeReceiver( 5130): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/GBoardtInterface( 2084): onReloaded()
,I/GBoardWebViewClient( 2084): onPageFinished url:file:///android_asset/www/main.html
,I/ActivityManager( 1030): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6150 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/BoardContentProvider( 2728): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2728): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/ActionManagerService( 1920): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2728): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2728): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1920): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2728): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2728): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2728): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2728): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2728): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2084): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
,D/GBoardWebViewUtils( 2084): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2084): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2084): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2084): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2084): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
E/SQLiteDatabase( 6150): Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
E/SQLiteDatabase( 6150): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6150): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6150): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6150): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6150): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6150): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6150): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6150): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6150): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6150): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6150): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6150): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6150): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6150): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6150): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/SQLiteDatabase( 6150): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 6150): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 6150): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 6150): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 6150): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 6150): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 6150): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 6150): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6150): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6150): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 6150): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6150): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDat,abase( 6150): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 6150): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/LifetrackerProvider2( 6150): Unable to open database for writing.
E/LifetrackerProvider2( 6150): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LifetrackerProvider2( 6150): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LifetrackerProvider2( 6150): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LifetrackerProvider2( 6150): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LifetrackerProvider2( 6150): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LifetrackerProvider2( 6150): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LifetrackerProvider2( 6150): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LifetrackerProvider2( 6150): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/LifetrackerProvider2( 6150): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/LifetrackerProvider2( 6150): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LifetrackerProvider2( 6150): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/LifetrackerProvider2( 6150): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/LifetrackerProvider2( 6150): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/LifetrackerProvider2( 6150): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/LifetrackerProvider2( 6150): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/LifetrackerProvider2( 6150): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/LifetrackerProvider2( 6150): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/LifetrackerProvider2( 6150): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/LifetrackerProvider2( 6150): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/LifetrackerProvider2( 6150): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/LifetrackerProvider2( 6150): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/LifetrackerProvider2( 6150): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/LifetrackerProvider2( 6150): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LifetrackerProvider2( 6150): 	at android.os.Looper.loop(Looper.java:135)
E/LifetrackerProvider2( 6150): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/LifetrackerProvider2( 6150): 	at java.lang.reflect.Method.invoke(Native Method)
E/LifetrackerProvider2( 6150): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/LifetrackerProvider2( 6150): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/LifetrackerProvider2( 6150): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/ActivityThread( 6150): Failed to find provider info for com.lge.lgaccount.provider

```
