#### Test 50388019b17f598_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/CheckinService( 2332): Done disabling old GoogleServicesFramework version
,I/[SystemUI]LGPowerUI( 1461): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1461): On Skip Timer : true
--------- beginning of system
D/WifiController( 1031): battery changed pluggedType: 2
D/LGDMClient( 3981): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3981): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/KeyguardUpdateMonitor( 1461): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
I/[SystemUI]LGPowerUI( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1973): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1973): Battery Level Remaining: 100%
D/LEDHandler( 1973): Battery Temp: 300, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/AndroidRuntime( 5910): 
D/AndroidRuntime( 5910): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5910): CheckJNI is OFF
I/art     ( 1031): Explicit concurrent mark sweep GC freed 17740(805KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.963ms total 206.476ms
D/AndroidRuntime( 5910): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1031): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1973): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1031): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
V/ActivityStackEx( 1031): create ActivityStackEx
D/LgeAbsQuickCoverView( 1411): mCoverXPos: 0 ,mCoverYPos: 0
D/LgeAbsQuickCoverView( 1411): mCoverWidth: 0 ,mCoverHeight: 0
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{1f396780 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{1f396780 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1031): AppWindowTokenEx init.. 
E/GBMv2   (  353): DFP En is all cleared set to be enabled
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{31ac5e55 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ActivityManager( 1031): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5938 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5910): Shutting down VM
V/ActivityManager( 1031): Display changed displayId=0
D/DSDPConnection( 1867): Display #0 changed.
D/SplitWindowPolicy( 1973): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1973): topRunningActivity=ActivityInfo{11472b7a co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1973): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1973): topRunningActivity=ActivityInfo{24e8df2b co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/ContextHelper( 5938): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/WebViewFactory( 5938): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 5938): Loading: webviewchromium
I/LibraryLoader( 5938): Time to load native libraries: 3 ms (timestamps 6126-6129)
I/LibraryLoader( 5938): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5938): Binding Chromium to main looper Looper (main, tid 1) {8974477}
I/LibraryLoader( 5938): Expected native library version number "",actual native library version number ""
I/chromium( 5938): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5938): Initializing chromium process, renderers=0
W/art     ( 5938): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5938): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  331): registerClient() client 0xb14fd8c0, uid 10318
D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1521480a:true
D/BluetoothAdapter( 5938): 709794020: getState() :  mService = null. Returning STATE_OFF
W/chromium( 5938): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5938): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5938): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 5938): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5938): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5938): Build Date: 12/12/14 금
I/Adreno-EGL( 5938): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5938): Remote Branch: 
I/Adreno-EGL( 5938): Local Patches: 
I/Adreno-EGL( 5938): Reconstruct Branch: 
W/chromium( 5938): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 5938): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5938): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5938): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5938): CordovaWebView is running on device made by: LGE
W/art     ( 5938): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5938): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5938): Render dirty regions requested: true
I/OpenGLRenderer( 5938): Initialized EGL, version 1.4
D/OpenGLRenderer( 5938): Enabling debug mode 0
D/Atlas   ( 5938): Validating map...
D/SplitWindow( 1031): check instance of lgWin Window{27249674 u0 com.example.hello/com.example.hello.MainActivity}
D/LgDataFeature( 5938): LgDataFeature() Constructor: none
D/LgDataFeature( 5938): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1031): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1031): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1031): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1031): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@fd56cb5,  pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1461): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/SystemUI[Framework]( 1031): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1031): Displayed com.example.hello/.MainActivity: +552ms (total +678ms)
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{15fa41b9 u0 com.example.hello/.MainActivity t2} time:76523
I/Timeline( 5938): Timeline: Activity_idle id: android.os.BinderProxy@2ffc0314 time:76529
I/chromium( 5938): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 5938): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 5938): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5938): 
D/JsMessageQueue( 5938): Set native->JS mode to OnlineEventsBridgeMode
I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
I/chromium( 5938): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5938): 
D/jxcore_app_log( 5938): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435331328
D/JX-Cordova( 5938): jxcore cordova android initializing
W/jxcore-log( 5938): Initializing JXcore engine
W/jxcore-log( 5938): JXcore engine is ready
W/jxcore-log( 5938): Starting JXcore engine
E/GBMv2   (  353): DFP En is all cleared set to be enabled
E/GBMv2   (  353): Set value is all cleared set the max
I/GBMv2   (  353): DFP Enabled. Ignore VFP set
W/m.example.hello( 5938): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8466]" dev="sockfs" ino=8466 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 5938): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 5938): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[9893]" dev="sockfs" ino=9893 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 5938): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/m.example.hello( 5938): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[28636]" dev="sockfs" ino=28636 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 5938): Platform android
W/jxcore-log( 5938): 
W/jxcore-log( 5938): Process ARCH arm
W/jxcore-log( 5938): 
I/jxcore-log( 5938): JXcore Cordova bridge is ready!
I/jxcore-log( 5938): 
W/jxcore-log( 5938): JXcore engine is started
,E/jxcore-log( 5938): >> LGE-LG-D855
E/jxcore-log( 5938): 
I/jxcore-log( 5938): Total memory 2995761152
I/jxcore-log( 5938): 
I/jxcore-log( 5938): Free memory 644886528
I/jxcore-log( 5938): 
I/jxcore-log( 5938): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5938): 
I/jxcore-log( 5938): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5938): 
I/jxcore-log( 5938): userPath [ 'www' ]
I/jxcore-log( 5938): 
I/jxcore-log( 5938): Size 1440 2392
I/jxcore-log( 5938): 
I/jxcore-log( 5938): Screen Brightness 50
I/jxcore-log( 5938): 
E/jxcore-log( 5938): Dummy Error Log.
E/jxcore-log( 5938): 
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 77751532733; DSPS: 2688501; Offset : -4307002586
I/jxcore-log( 5938): getBuffer is called!!!!
I/jxcore-log( 5938): 
,I/ActivityManager( 1031): Killing 5193:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5193/cgroup.procs: No such file or directory
,D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1031): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService( 1031): Message: 2
D/WifiService( 1031): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1031): setWifiEnabled: false pid=5938, uid=10318, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1031): setWifiEnabled: false pid=5938, uid=10318
E/WifiService( 1031): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 5938): ****TEST TOOK:  5066  ms ****
I/jxcore-log( 5938): 
I/jxcore-log( 5938): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5938): 
D/InitAlarmsService( 4879): Clearing and rescheduling alarms.
,I/ActivityManager( 1031): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6004 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 6004): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6004): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3651a99b
,D/CalendarProvider2( 6004): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6004): Created com.android.providers.calendar.CalendarAlarmManager@2a4e98e4(com.android.providers.calendar.CalendarProvider2@3651a99b)
D/CalendarProvider2( 6004): Scheduling check of next Alarm
,D/CalendarProvider2( 6004): SCHEDULE_ALARM_REMOVE
I/ActivityManager( 1031): Killing 4879:com.android.calendar/u0a13 (adj 15): empty #17
D/AndroidRuntime( 6006): 
D/AndroidRuntime( 6006): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6006): CheckJNI is OFF
W/libprocessgroup( 1031): failed to open /acct/uid_10013/pid_4879/cgroup.procs: No such file or directory
,D/AndroidRuntime( 6006): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1031): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1031): Killing 5938:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/WindowState( 1031): WIN DEATH: Window{27249674 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1031): Client connection lost with reason: 4
D/InputDispatcher( 1031): Window went away: Window{27249674 u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings( 1031): Skipping PackageSetting{35fe72ba com.test.thalitest/10311} due to missing metadata
,E/libprocessgroup( 1031): failed to kill 1 processes for processgroup 5938
,I/ActivityManager( 1031):   Force finishing activity ActivityRecord{15fa41b9 u0 com.example.hello/.MainActivity t2}
,E/GBMv2   (  353): DFP En is all cleared set to be enabled
,W/ActivityManager( 1031): Spurious death for ProcessRecord{1fbe405b 5938:com.example.hello/u0a318}, curProc for 5938: null
I/ActivityManager( 1031): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1031):   Force finishing activity ActivityRecord{15fa41b9 u0 com.example.hello/.MainActivity t2 f}
W/ActivityManager( 1031): Duplicate finish request for ActivityRecord{15fa41b9 u0 com.example.hello/.MainActivity t2 f}
,I/[LGHome]EVENT( 2082): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1973): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1973): topRunningActivity=ActivityInfo{31684f88 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2082): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1973): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1973): topRunningActivity=ActivityInfo{1cd57d21 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2082): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowManager( 1031): removeStackAndNeedHomeResume ActivityStack{1cff50f8 stackId=1, 0 tasks}
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1831): Ignoring removeGeofence because network location is disabled.
,D/LIA_MrGDBLogger_PackageInfoDetector( 2719): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
D/LIA_Service_RemotePackageHandler( 2043): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
I/InputReader( 1031): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 4226): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 4226): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4226): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4226): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4226): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4226): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4226): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4226): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4226): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4226): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4226): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4226): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/art     ( 4266): Explicit concurrent mark sweep GC freed 15582(911KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 637us total 73.568ms
,I/ActivityManager( 1031): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6071 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ActionManagerService( 1918): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 2719): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2082): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2082): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1461): onReceive = android.intent.action.PACKAGE_REMOVED
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,I/[LGHome]EVENT( 2082): [Launcher.java:1114:onPause()]onPause
,D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1461): createShortcutInfo...
D/ActionManagerService( 1918): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 2719): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 2719): handleMessage: what(1000) actionID(0x1000004)
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
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1447937693376
I/GBoardWebViewUtils( 2082): , create_time: 1447937694406
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1447937693376&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
D/WallpaperManager( 2082): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1461): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
,I/SystemUI[Framework]( 1031): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1031): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1031): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1031): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@fd56cb5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/art     ( 1031): Explicit concurrent mark sweep GC freed 12606(973KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 12.584ms total 160.329ms
I/art     ( 1031): WaitForGcToComplete blocked for 61.812ms for cause Explicit
D/SplitUIManager( 1884): split_name #11 / not available #0
D/SplitUIService( 1884): removed split : 
,W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/ResourcesManager( 6071): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
D/SplitUIManager( 1884): split_name #11 / not available #0
I/SplitUIService( 1884): split app #11
D/administrator( 1031): Handling package changes for user 0
D/PluginManager( 6071): init()
,D/KeyguardModel( 1461): handleShortcutListChanged...
D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1461): createShortcutInfo...
,D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,I/[LGHome]EVENT( 2082): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
D/KeyguardModel( 1461): handleShortcutListChanged...
I/NotificationService( 1031): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService( 1031): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1031): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
D/TaskPersister( 1031): removeObsoleteFile: deleting file=2_task.xml
D/PhoneStatusBar( 1461): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/CalendarProvider2( 6004): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6004): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 1031): Killing 5585:com.google.android.apps.docs/u0a61 (adj 15): empty #17
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2082): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
I/art     ( 1031): Explicit concurrent mark sweep GC freed 7156(398KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.374ms total 234.419ms
D/AndroidRuntime( 6006): Shutting down VM
,W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup( 1031): failed to open /acct/uid_10061/pid_5585/cgroup.procs: No such file or directory
W/ResourceType( 1031): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{25fc5c88 u0 com.lge.launcher2/.Launcher t1} time:84368
D/[Concierge]Service( 2609): onStartCommand(). Type : 8
D/[Concierge]Service( 2609): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]WidgetView( 2082): change position of spinner
,D/[Concierge]Service( 2609): Update widget ID : 11
I/[Concierge]WidgetView( 2082): initWebView(). Time : 1448386027736
D/[Concierge]Service( 2609): onStartCommand(). Type : 0
I/[Concierge]WebView( 2082): Return exist ConciergeWebView. Reuse : 759935863
D/[Concierge]WidgetView( 2082): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2082): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@110b303b
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2082): isWidgetUpdateSkippable ? true
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetBroadcastReceiver( 2082): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/[Concierge]WidgetView( 2082): Widget kill message received. Destory myself. My : 1448385971712, New one : 1448386027736
D/[Concierge]WidgetView( 2082): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2082): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ExternalStrings( 6071): load override strings
W/ExternalStrings( 6071): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6071): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6071): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6071): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6071): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6071): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6071): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6071): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6071): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6071): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6071): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6071): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6071): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6071): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6071): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6071): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6071): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6071): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 6071): onCreate
I/Timeline( 2082): Timeline: Activity_idle id: android.os.BinderProxy@1e74e3d4 time:84519
V/Signer  ( 6071): override build config not found
D/Signer  ( 6071): value of property debug is false
,D/LGMDMWrapper( 6071): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 6071): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6071): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6071): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6071): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6071): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6071): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6071): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6071): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6071): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6071): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6071): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6071): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 6071): Create singleton instance
,D/LGMDMWrapper( 6071): LG MDM library v4.0.0 is available on this device.
,D/PostponalbeReceiver( 6071): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,W/ContextImpl( 6071): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
E/SQLiteLog( 5501): (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
E/SQLiteDatabase( 5501): Error inserting package=com.example.hello
E/SQLiteDatabase( 5501): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5501): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5501): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
E/SQLiteDatabase( 5501): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 5501): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5501): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
E/SQLiteDatabase( 5501): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
E/SQLiteDatabase( 5501): 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
E/SQLiteDatabase( 5501): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 5501): 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
E/SQLiteDatabase( 5501): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
E/SQLiteDatabase( 5501): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
E/SQLiteDatabase( 5501): 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
E/SQLiteDatabase( 5501): 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
E/SQLiteDatabase( 5501): 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
E/SQLiteDatabase( 5501): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/SQLiteDatabase( 5501): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/SQLiteDatabase( 5501): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
E/SQLiteDatabase( 5501): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5501): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5501): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 5501): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5501): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5501): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 5501): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1031): Killing 5682:com.lge.eula/1000 (adj 15): empty #17
,I/chromium( 2082): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)

```
