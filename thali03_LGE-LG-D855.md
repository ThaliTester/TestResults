#### Test 61699762a45f11c_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 78177780025; DSPS: 2703029; Offset : -4324768628
,D/UEI.SmartControl( 6041): Internal timer expired: 1
D/UEI.SmartControl( 6041): unbind internal service
D/serial_port( 6041): close(fd = 25)
I/UEI.SmartControl( 6041): Serial port is closed.
D/AndroidRuntime( 6097): 
D/AndroidRuntime( 6097): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6097): CheckJNI is OFF
D/AndroidRuntime( 6097): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1057): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1951): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1057): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1057): setTaskToReturnTo : TaskRecord{245fdc88 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1057): setTaskToReturnTo : TaskRecord{245fdc88 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1057): AppWindowTokenEx init.. 
E/GBMv2   (  333): DFP En is all cleared set to be enabled
I/ActivityManager( 1057): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6112 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/InputDispatcher( 1057): Focus left window: Window{24724994 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 2044): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/AndroidRuntime( 6097): Shutting down VM
V/ActivityManager( 1057): Display changed displayId=0
D/DSDPConnection( 1862): Display #0 changed.
D/SplitWindowPolicy( 1951): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1951): topRunningActivity=ActivityInfo{3a1c7b6c co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1951): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1951): topRunningActivity=ActivityInfo{d43a535 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6112): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,I/WebViewFactory( 6112): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6112): Loading: webviewchromium
I/LibraryLoader( 6112): Time to load native libraries: 5 ms (timestamps 9142-9147)
I/LibraryLoader( 6112): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6112): Binding Chromium to main looper Looper (main, tid 1) {340bd225}
I/LibraryLoader( 6112): Expected native library version number "",actual native library version number ""
I/chromium( 6112): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6112): Initializing chromium process, renderers=0
W/art     ( 6112): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6112): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  318): registerClient() client 0xb148f740, uid 10311
D/BluetoothManagerService( 1057): Message: 20
D/BluetoothManagerService( 1057): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@142ed4d2:true
W/chromium( 6112): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6112): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6112): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6112): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6112): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6112): Build Date: 12/12/14 금
I/Adreno-EGL( 6112): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6112): Remote Branch: 
I/Adreno-EGL( 6112): Local Patches: 
I/Adreno-EGL( 6112): Reconstruct Branch: 
W/chromium( 6112): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6112): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6112): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6112): onDetachedFromWindow called when already detached. Ignoring
I/PhoneWindow( 6112): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 6112): [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 6112): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 6112): CordovaWebView is running on device made by: LGE
W/art     ( 6112): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6112): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1057): Activity pause timeout for ActivityRecord{b328621 u0 com.test.thalitest/.MainActivity t4}
D/OpenGLRenderer( 6112): Render dirty regions requested: true
I/OpenGLRenderer( 6112): Initialized EGL, version 1.4
D/OpenGLRenderer( 6112): Enabling debug mode 0
D/Atlas   ( 6112): Validating map...
D/SplitWindow( 1057): check instance of lgWin Window{10352efc u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6112): LgDataFeature() Constructor: none
D/LgDataFeature( 6112): LgDataFeature() Constructor Done, null
D/WindowManager( 1057): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/[SystemUI]NavigationThemeResource( 1497): notify navigation bar color(0xfff5f5f5)
I/[SystemUI]NavigationThemeResource( 1497): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1497):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1497): , Keyguard show=false, IME shown=false, Panel expanded=false
I/SystemUI[Framework]( 1057): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
W/PhoneWindowManagerEx( 1057): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1057): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1057): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1057): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d3d78fb,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1057): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher( 1057): Focus entered window: Window{10352efc u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputMethodManagerService( 1057): setImestate : 0
I/ActivityManager( 1057): Displayed com.test.thalitest/.MainActivity: +667ms (total +790ms)
I/Timeline( 1057): Timeline: Activity_windows_visible id: ActivityRecord{b328621 u0 com.test.thalitest/.MainActivity t4} time:79595
W/IInputConnectionWrapper( 6112): showStatusIcon on inactive InputConnection
I/Timeline( 6112): Timeline: Activity_idle id: android.os.BinderProxy@2b456338 time:79602
W/IInputConnectionWrapper( 6112): getTextBeforeCursor on inactive InputConnection
E/b       ( 1729): Unable to connect to the editor to retrieve text... will retry later
W/IInputConnectionWrapper( 6112): getTextAfterCursor on inactive InputConnection
D/JsMessageQueue( 6112): Set native->JS mode to OnlineEventsBridgeMode
E/GBMv2   (  333): DFP En is all cleared set to be enabled
E/GBMv2   (  333): Set value is all cleared set the max
I/GBMv2   (  333): DFP Enabled. Ignore VFP set
D/jxcore_app_log( 6112): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435204736
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6112): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6112):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6112):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6112):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6112):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6112): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24314705 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112):     - Bluetooth MAC address: 58:3F:54:73:64:C0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b740a68 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6112): addListener: New listener added - the number of listeners is now 1
D/WifiService( 1057): New client listening to asynchronous messages
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 6112): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 6112): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 6112): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 6112): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 6112): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 6112): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 6112): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 6112): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 6112): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 6112): 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 6112): 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
W/System.err( 6112): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6112): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6112): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 6112): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6112): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6112): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44e81 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86eb26 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6112): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6112): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 6112): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 6112): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 6112): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 6112): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 6112): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 6112): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 6112): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 6112): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 6112): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 6112): 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 6112): 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
W/System.err( 6112): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6112): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6112): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/chromium( 6112): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6112): 
,I/chromium( 6112): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6112): 
,I/ActivityManager( 1057): Waited long enough for: ServiceRecord{1cbe2703 u0 com.google.android.music/.wear.WearMetadataSyncService}
,I/[SystemUI]QPairHandler( 1497): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1879): replaced split : contains_com.google.android.talk / true
I/InputReader( 1057): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1497): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1497): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
D/SplitUIManager( 1879): split_name #11 / not available #0
I/SplitUIService( 1879): split app #11
,D/administrator( 1057): Handling package changes for user 0
,I/AppUp4:CustModeStarterReceiver( 5710): onReceive
,D/AppUp4:CustFacade( 5710): Context : android.app.ReceiverRestrictedContext@3f22438f
D/AppUp4:CustFacade( 5710): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5710): isPhone : true
D/AppUp4:CustModeStarterReceiver( 5710): begin check event
I/AppUp4:CustModeStarterReceiver( 5710): Event For Nothing, skip.
D/InitAlarmsService( 5031): Clearing and rescheduling alarms.
,I/NotificationService( 1057): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1057): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/ActivityManager( 1057): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6225 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
W/ResourcesManager( 1057): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/UpdateIcingCorporaServi( 4413): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/[LGHome]EVENT( 2044): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
D/LockScreenSettings( 5843): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5843): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5843): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5843): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5843): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 5843): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
W/ResourcesManager( 2044): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[LGHome]Launcher( 2044): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/PackageBroadcastService( 2385): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
W/ResourcesManager( 6225): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/PeopleContactsSync( 2385): CP2 sync disabled
V/SIM_STK ( 1057): Menu title from STK is T-Mobile
,W/ResourcesManager( 4413): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4413): UpdateCorporaTask done [took 86 ms] updated apps [took 86 ms] 
D/CalendarProvider2( 6225): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2859aaf0
W/ResourcesManager( 1057): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1057): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 2044): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/art     ( 1057): Explicit concurrent mark sweep GC freed 23530(1169KB) AllocSpace objects, 3(54KB) LOS objects, 33% free, 44MB/66MB, paused 2.125ms total 99.075ms
,D/CalendarProvider2( 6225): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6225): Created com.android.providers.calendar.CalendarAlarmManager@340bd225(com.android.providers.calendar.CalendarProvider2@2859aaf0)
D/CalendarProvider2( 6225): Scheduling check of next Alarm
D/CalendarProvider2( 6225): SCHEDULE_ALARM_REMOVE
,I/ActivityManager( 1057): Killing 5031:com.android.calendar/u0a13 (adj 15): empty #17
W/libprocessgroup( 1057): failed to open /acct/uid_10013/pid_5031/cgroup.procs: No such file or directory
,I/chromium( 6112): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 6112): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
I/CalendarProvider2( 6225): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6225): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 1057): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6259 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1057): Killing 5750:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1057): failed to open /acct/uid_10023/pid_5750/cgroup.procs: No such file or directory
W/ResourcesManager( 6259): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6259): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6259): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6259): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1d5792ee, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3f22438f, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@21c6861c, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@340bd225, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@30adeffa, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@e8989ab, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3dc3e808, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3b4c6ba1, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@27db11c6, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3cd51587, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@b37cb4, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@23a320dd, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@28668452, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@19638323, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3165b020, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1cb5edd9, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@36c4939e, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@e12e7f, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3145ae4c, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@108e8e95, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@18624baa, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@464339b, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2b456338, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@6167f11, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@a717876, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@26486e77, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@5897ae4, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2f52fb4d, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1974a602, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@8cb7b13, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1d56150, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1f60ff49, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@258b204e, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2a68b56f, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@38b7427c, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@24314705, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1f7cf35a, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@bf5398b, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1b740a68, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@44e81, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@a86eb26, lg_preferences_recent_time,zones=com.android.calendar.adaptation.PreferenceKey$KeyData@1c7be367, lg_p
D/GeneralPreferenceUtils( 6259): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,D/Config  ( 6259): [init]
I/Config  ( 6259): LGCalendar ver.4.40.16
I/Config  ( 6259): start check model
I/Config  ( 6259): start check native_ca
,I/Config  ( 6259): Config Operator=OPEN, Country=EU
D/Config  ( 6259): [setDefaultValuesToPref]
D/Config  ( 6259): [parseProfiles]
D/ProfilesParser( 6259): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6259): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6259): [updateProfiletoCountryInfo]
D/GeneralPreference( 6259): [checkAndMigrateOldPreference]
D/AlertReceiver( 6259): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6259): Start InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6259): onHandleIntent
D/HolidayDataLoader( 6259): readJsonAsset : holiday.json
,I/AlertUtils( 6259): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
D/AlertService( 6259): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6259): [updateWidgets] 
,D/MonthWidgetProvider( 6259): [onReceive]
D/CalendarWidgetProvider( 6259): [onReceive]
D/CalendarWidgetProvider( 6259): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6259): [onCreate] mContext.getPackageName() = com.android.calendar
I/AlertUtils( 6259): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,D/WeekWidgetProvider( 6259): [onReceive]
D/CalendarWidgetProvider( 6259): [onReceive]
D/CalendarWidgetProvider( 6259): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
D/CalendarTypeController( 6259): [onCreate] mContext.getPackageName() = com.android.calendar
I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
,I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
E/HolidayIntentService( 6259): onHandleIntent:holiday data empty
,I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6259): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6259): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6259): set default noti to content://media/internal/audio/media/41
,I/InitNotificationRingtoneService( 6259): End InitializeAlertRingtoneService.onHandleIntent
D/LIA_MrGDBLogger_MrGIntentReceiverDBCleaning( 2780): [dreamwood]onReceive
,V/AlarmManager( 1057): RTC_WAKEUP set : Alarm{21e9a0ee type 0 when 1457092438128 com.lge.ia.task.mrgdblogger} when 1457092438128
D/LIA_MrGDBLogger_MrGDBCleaner( 2780): [dreamwood]onReceive
,V/AlarmManager( 1057): RTC_WAKEUP set : Alarm{3a1a441c type 0 when 1457092470597 com.android.vending} when 1457092470597
V/AlarmManager( 1057): ELAPSED_WAKEUP set : Alarm{797b825 type 2 when 89420 com.android.providers.calendar} when 89420
D/LIA_MrGDBLogger_MrGDBManager( 2780): [dreamwood]dbFileSize : 61440
D/LIA_MrGDBLogger_DBCleanerUtil( 2780): [dreamwood]cleanOldRecord : APP_USAGE
D/LIA_MrGDBLogger_DBCleanerUtil( 2780): [dreamwood]LimitedDate : 2016-02-03 12:54:33, count : 0
D/LIA_MrGDBLogger_DBCleanerUtil( 2780): [dreamwood]cleanOldRecord : CONCIERGE_BOARD
D/LIA_MrGDBLogger_DBCleanerUtil( 2780): [dreamwood]LimitedDate : 2016-02-03 12:54:33, count : 0
D/LIA_MrGDBLogger_DBCleanerUtil( 2780): [dreamwood]cleanOldRecord : INFORMANT_FEATURE_STATUS_INFO
D/LIA_MrGDBLogger_DBCleanerUtil( 2780): [dreamwood]LimitedDate : 2016-02-03 12:54:33, count : 0
D/LIA_MrGDBLogger_MrGDBManager( 2780): [dreamwood]dbFileSize : 61440
,D/CalendarProviderBroadcastReceiver( 6225): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6225): [IntentService] WakeLock acquire, start IntentSerivce
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1057): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CalendarProvider2( 6225): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6225): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6225): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6225): (284) automatic index on view_events(_id)
D/CalendarProvider2( 6225): [IntentService] Release Lock
,D/CalendarProvider2( 6225): CalendarProviderIntentService.onDestroy()
V/SIM_STK ( 1057): Menu title from STK is T-Mobile
,D/AlertService( 6259): Beginning updateAlertNotification
,D/AlertService( 6259): No fired or scheduled alerts
,D/AlertService( 6259): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6259): No events found starting within 1 week.
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2084): Explicit concurrent mark sweep GC freed 16902(932KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.869ms total 63.734ms
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5930): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5930): [1] 5.onFinished: Scheduling replication attempt 1.
I/ActivityManager( 1057): Killing 4831:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1057): failed to open /acct/uid_1000/pid_4831/cgroup.procs: No such file or directory
,V/AlarmManager( 1057): ELAPSED_WAKEUP set : Alarm{3d04ec4c type 2 when 91935 com.google.android.gms} when 91935
,E/ThermalEngine(  327): out low battery limit. 
,V/AlarmManager( 1057): ELAPSED_WAKEUP set : Alarm{2d158549 type 2 when 96603 com.google.android.gms} when 96603
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1057): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 98179418312; DSPS: 3358443; Offset : -4324778317
,I/rmt_storage(  311): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  311): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  311): wakelock acquired: 1, error no: 42
,I/rmt_storage(  311): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  311): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  311): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  311): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  311): 
,I/rmt_storage(  311): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,E/Diag_Lib(  914): [IMS_FATAL]| 3347 | 933 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/MusicWidget( 2652): mDelayedStopHandler : unbind
,I/MusicBrowser( 2160): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2160): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2160): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/MusicBrowser( 2160): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2160): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2160): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2160): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2160): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1057):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@464339bcom.lge.music.MediaPlaybackService$5@2b456338
D/MusicBrowser( 2160): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2160): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2160): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2160): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2160): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@27db11c6
I/MusicBrowser( 2160): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2160): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2160): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2160): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2160): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2160): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2160): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2160): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2160): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2160): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2160): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2160): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2160): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2160): reset
V/MediaPlayer[Native]( 2160): setListener
V/MediaPlayer[Native]( 2160): disconnect
V/MediaPlayer[Native]( 2160): destructor
,V/AudioFlinger(  318): releasing 13 from 2160 for -1
V/AudioFlinger(  318):  decremented refcount to 0
V/AudioFlinger(  318): purging stale effects
V/MediaPlayer[Native]( 2160): disconnect
D/MusicBrowser( 2160): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2160): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2160): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2160): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2160): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2160): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2160): [SmartShareManagerClient] unregisterListener: 102137617
W/SmartShareClient( 2160): [SmartShareManagerClient] unregisterListener invalid listener: 102137617
I/SmartShareClient( 2160): [SmartShareManagerClient] terminate service: 2160/MediaPlaybackService/566658588
E/HomeCloudIF( 2160): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2160): [SmartShareManagerClient] unbindService context:android.app.Application@a717876
,V/CloudHub( 2160): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2160): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2160): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2160): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/ActivityManager( 1057): Killing 5799:com.google.android.apps.docs/u0a61 (adj 15): empty #17
I/CloudHub( 2160): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
,W/libprocessgroup( 1057): failed to open /acct/uid_10061/pid_5799/cgroup.procs: No such file or directory
,I/CloudHub( 2160): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19979
,V/AlarmManager( 1057): RTC_WAKEUP set : Alarm{2e0fab6f type 0 when 1457092493925 com.android.vending} when 1457092493925,
,W/ContextImpl( 4361): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SIM_STK ( 1057): Menu title from STK is T-Mobile
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5930): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5930): [1] 5.onFinished: Scheduling replication attempt 2.
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 118181516632; DSPS: 4013871; Offset : -4324755192
,I/[SystemUI]LGPowerUI( 1497): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1497): On Skip Timer : true
W/Settings( 1057): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1057): battery changed pluggedType: 2
W/Settings( 1057): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3793): Disconnected process message: 10, size: 0
D/LEDHandler( 1951): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1951): Battery Level Remaining: 100%
D/LEDHandler( 1951): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1497): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1497): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1497): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4166): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4166): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/MainApplication( 6014): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/CloudHub( 2160): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2160): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
D/PowerManagerServiceEx( 1057): acquireWakeLockInternal: lock=21844665, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1057
,V/AlarmManager( 1057): RTC_WAKEUP set : Alarm{2b684e5f type 0 when 1457092519904 com.android.vending} when 1457092519904
,D/[Concierge]Service( 2633): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1057): releaseWakeLockInternal: lock=21844665 [*alarm*], flags=0x0
,V/SIM_STK ( 1057): Menu title from STK is T-Mobile
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 138183500683; DSPS: 4669297; Offset : -4324785301
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5930): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5930): [1] 5.onFinished: Scheduling replication attempt 3.
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 158184877041; DSPS: 5324702; Offset : -4324782339
,V/AlarmManager( 1057): RTC_WAKEUP set : Alarm{199414ba type 0 when 1457092541061 com.android.vending} when 1457092541061
,V/SIM_STK ( 1057): Menu title from STK is T-Mobile
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5930): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5930): [1] 5.onFinished: Scheduling replication attempt 4.
I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 178186344420; DSPS: 5980110; Offset : -4324779751
,V/AlarmManager( 1057): ELAPSED_WAKEUP set : Alarm{2325c50c type 2 when 188278 android} when 188278
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1057): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/AlarmManager( 1057): ELAPSED_WAKEUP set : Alarm{2c66be55 type 2 when 168194 com.google.android.gms} when 168194
V/AlarmManager( 1057): ELAPSED_WAKEUP set : Alarm{7b206a type 2 when 181555 com.google.android.gms} when 181555
V/AlarmManager( 1057): RTC_WAKEUP set : Alarm{2ef025f8 type 0 when 1457092568471 com.android.vending} when 1457092568471
,D/[Concierge]Service( 2633): onStartCommand(). Type : 9
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1057): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/SIM_STK ( 1057): Menu title from STK is T-Mobile
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5930): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5930): [1] 5.onFinished: Scheduling replication attempt 5.
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 198187835074; DSPS: 6635519; Offset : -4324784458
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 218189232168; DSPS: 7290924; Offset : -4324760656
,V/AlarmManager( 1057): RTC_WAKEUP set : Alarm{18b1fbe6 type 0 when 1457092598748 com.android.vending} when 1457092598748
,V/SIM_STK ( 1057): Menu title from STK is T-Mobile
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1057): Explicit concurrent mark sweep GC freed 22616(987KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.973ms total 148.635ms
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5930): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5930): [1] 5.onFinished: Giving up after 6 failures.
I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 238190713892; DSPS: 7946333; Offset : -4324774292
,I/[SystemUI]LGPowerUI( 1497): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1497): On Skip Timer : true
,W/Settings( 1057): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1057): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1057): battery changed pluggedType: 2
D/HeadsetStateMachine( 3793): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1497): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1497): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1951): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1951): Battery Level Remaining: 100%
D/LEDHandler( 1951): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1497): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4166): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4166): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/MainApplication( 6014): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/PowerManagerServiceEx( 1057): acquireWakeLockInternal: lock=21844665, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1057
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1057): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/[Concierge]Service( 2633): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1057): releaseWakeLockInternal: lock=21844665 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 258192202912; DSPS: 8601741; Offset : -4324750064
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 278193579280; DSPS: 9257148; Offset : -4324807892
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
,I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 298195044386; DSPS: 9912555; Offset : -4324777373
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 318196378148; DSPS: 10567959; Offset : -4324786385
,I/[SystemUI]LGPowerUI( 1497): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1497): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1497): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1497): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1951): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1951): Battery Level Remaining: 100%
D/LEDHandler( 1951): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/WifiController( 1057): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1497): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1057): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1057): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3793): Disconnected process message: 10, size: 0
D/LGDMClient( 4166): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4166): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/MainApplication( 6014): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/LocationManagerService( 1057): remove 3dc58af5
D/LocationManagerService( 1057): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService( 1057): getAllProviders()=[passive, gps, network]
D/LocationManagerService( 1057): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 1057): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService( 1057): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 338197818673; DSPS: 11223366; Offset : -4324780055
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 358199249147; DSPS: 11878773; Offset : -4324783960
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1057): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1057): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1057): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1057): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1057): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1057): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ResourcesManager( 1435): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1435): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1435): onNotificationPosted
D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do add job
D/LgeQuickCoverNotificationData( 1435): add : 2
D/LgeQuickCoverNotificationData( 1435): do add job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
W/ResourcesManager( 1497): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1497): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
E/PlayEventLogger( 5930): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5930): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5930): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5930): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5930): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5930): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5930): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3f474d62 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 5930): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1057): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 378200702469; DSPS: 12534181; Offset : -4324795586
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 398202100908; DSPS: 13189586; Offset : -4324770333
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 418203517323; DSPS: 13844993; Offset : -4324788218
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 438204866441; DSPS: 14500397; Offset : -4324781926
,D/PowerManagerServiceEx( 1057): acquireWakeLockInternal: lock=21844665, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1057
,V/AlarmManager( 1057): ELAPSED_WAKEUP set : Alarm{e540f59 type 2 when 338743 com.google.android.gms} when 338743
,D/[Concierge]Service( 2633): onStartCommand(). Type : 9
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1057): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1057): releaseWakeLockInternal: lock=21844665 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 458206840908; DSPS: 15155821; Offset : -4324760480
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 478208289450; DSPS: 15811229; Offset : -4324776912
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 498211631793; DSPS: 16466698; Offset : -4324760907
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 518213186602; DSPS: 17122109; Offset : -4324762442
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 538214658327; DSPS: 17777518; Offset : -4324786156
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 558216049136; DSPS: 18432923; Offset : -4324768821
,I/[SystemUI]LGPowerUI( 1497): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1497): On Skip Timer : true
W/Settings( 1057): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1057): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1057): battery changed pluggedType: 2
D/LEDHandler( 1951): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1951): Battery Level Remaining: 100%
D/LEDHandler( 1951): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1497): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1497): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3793): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1497): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4166): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4166): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/MainApplication( 6014): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 578217919840; DSPS: 19088345; Offset : -4324790259
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
,I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 598219350878; DSPS: 19743751; Offset : -4324762848
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 618221399415; DSPS: 20399178; Offset : -4324759040
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 638223250959; DSPS: 21054599; Offset : -4324768938
,I/ActivityManager( 1057): Killing 5912:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1057): failed to open /acct/uid_1000/pid_5912/cgroup.procs: No such file or directory
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
,I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 658224679543; DSPS: 21710006; Offset : -4324774733
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1057): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1057): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1057): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1057): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1057): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5930): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5930): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5930): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5930): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5930): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5930): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5930): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5930): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1057): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3f474d62 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 678226135444; DSPS: 22365413; Offset : -4324752818
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 698228002031; DSPS: 23020835; Offset : -4324778661
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
,I/[SystemUI]DateView( 1497): called onTimeUpdated()
,I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 718229439415; DSPS: 23676242; Offset : -4324775629
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 738231464554; DSPS: 24331668; Offset : -4324764649
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 758233319783; DSPS: 24987089; Offset : -4324770993
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
,I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 778234753309; DSPS: 25642496; Offset : -4324771846
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 798236090779; DSPS: 26297900; Offset : -4324777018
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 818237953109; DSPS: 26953321; Offset : -4324776339
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
,I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 838239392237; DSPS: 27608728; Offset : -4324771510
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 858241456255; DSPS: 28264156; Offset : -4324782663
,D/PowerManagerServiceEx( 1057): acquireWakeLockInternal: lock=21844665, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1057
,V/AlarmManager( 1057): ELAPSED_WAKEUP set : Alarm{2a59c093 type 2 when 730879 com.google.android.gms} when 730879
,V/AlarmManager( 1057): RTC_WAKEUP set : Alarm{2595f8d0 type 0 when 1457093220030 com.google.android.gms} when 1457093220030
D/[Concierge]Service( 2633): onStartCommand(). Type : 9
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1057): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/PowerManagerServiceEx( 1057): releaseWakeLockInternal: lock=21844665 [*alarm*], flags=0x0
,I/EventLogService( 2385): Aggregate from 1457091419974 (log), 1457091419974 (data)
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 878243340536; DSPS: 28919578; Offset : -4324790393
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 898244801195; DSPS: 29574985; Offset : -4324764216
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 918246189500; DSPS: 30230391; Offset : -4324779641
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 938248071264; DSPS: 30885812; Offset : -4324759529
,D/PowerManagerServiceEx( 1057): acquireWakeLockInternal: lock=21844665, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1057
,V/AlarmManager( 1057): ELAPSED_WAKEUP set : Alarm{1b316085 type 2 when 942288 com.android.bluetooth} when 942288
,W/bt-smp  ( 3793): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3793): Plain text(LSB ~ MSB) = 08 dc 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3793): Encrypted text(LSB ~ MSB) = 11 a1 04 47 bb 42 08 12 8c e8 94 1a 0f 4d f0 da 
W/bt-btm  ( 3793): Stopping oneshot timer
D/[Concierge]Service( 2633): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1057): releaseWakeLockInternal: lock=21844665 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 958249561851; DSPS: 31541221; Offset : -4324764146
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1057): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1057): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1057): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1057): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1057): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5930): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5930): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5930): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5930): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5930): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5930): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5930): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5930): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/QuickStatusbarLayout( 1435): Notification difference=198
,D/DSQN    ( 1057): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3f474d62 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 978251640871; DSPS: 32196649; Offset : -4324760348
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 998253502161; DSPS: 32852070; Offset : -4324760734
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1018254952053; DSPS: 33507478; Offset : -4324775582
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1038256359307; DSPS: 34162884; Offset : -4324772266
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1058258199583; DSPS: 34818304; Offset : -4324763098
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
,I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1078259579502; DSPS: 35473709; Offset : -4324756313
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1098261559962; DSPS: 36129135; Offset : -4324790092
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1118263459680; DSPS: 36784557; Offset : -4324782620
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
,I/[SystemUI]DateView( 1497): called onTimeUpdated()
,I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1138264888527; DSPS: 37439963; Offset : -4324757346
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1158266287318; DSPS: 38095369; Offset : -4324762521
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1178267695774; DSPS: 38750775; Offset : -4324757639
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
,I/[SystemUI]DateView( 1497): called onTimeUpdated()
,I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1198269125114; DSPS: 39406182; Offset : -4324762832
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1218271040341; DSPS: 40061605; Offset : -4324770187
,I/UsageStatsService( 1057): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1238272380399; DSPS: 40717009; Offset : -4324772668
,I/[SystemUI]TimeTickManager( 1497): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1497): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1497): called onTimeUpdated()
I/[SystemUI]Clock( 1497): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1497): called onTimeUpdated()
,I/[SystemUI]DateView( 1497): called onTimeUpdated()
I/[SystemUI]DateView( 1497): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1497): handleTimeUpdate
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1258274058629; DSPS: 41372424; Offset : -4324773062
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1057): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1057): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1057): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1057): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1057): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5930): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5930): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5930): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5930): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5930): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5930): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5930): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5930): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1057): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3f474d62 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/sensors_hal_Time( 1057): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1057): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1057): tsOffsetIs: Apps: 1278275502437; DSPS: 42027831; Offset : -4324763683
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6718): 
D/AndroidRuntime( 6718): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6718): CheckJNI is OFF
D/AndroidRuntime( 6718): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1057): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1057): Killing 6112:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1057): WIN DEATH: Window{10352efc u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1057): Client connection lost with reason: 4
D/InputDispatcher( 1057): Focus left window: Window{10352efc u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher( 1057): Window went away: Window{10352efc u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1057): Skipping PackageSetting{ac7503 com.example.hello/10319} due to missing metadata
I/ActivityManager( 1057):   Force finishing activity ActivityRecord{b328621 u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  333): DFP En is all cleared set to be enabled
W/ActivityManager( 1057): Spurious death for ProcessRecord{318e1f30 6112:com.test.thalitest/u0a311}, curProc for 6112: null
I/ActivityManager( 1057): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1057):   Force finishing activity ActivityRecord{b328621 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1057): Duplicate finish request for ActivityRecord{b328621 u0 com.test.thalitest/.MainActivity t4 f}
D/SplitWindowPolicy( 1951): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1951): topRunningActivity=ActivityInfo{2b86bb3b co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1951): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1951): topRunningActivity=ActivityInfo{200be258 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2044): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2044): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2044): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2044): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1916): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2780): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2044): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/art     ( 4413): Explicit concurrent mark sweep GC freed 22385(1301KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 350us total 31.316ms
D/KeyguardModel( 1497): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1057): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1826): Ignoring removeGeofence because network location is disabled.
E/LGBluetoothAvrcpQcomAdapter( 3793): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3793): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2007): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2780): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/System.err( 4361): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4361): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4361): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4361): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4361): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4361): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4361): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4361): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4361): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4361): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4361): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4361): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1057): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6749 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/[LGHome]LGActivityUtil( 2044): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2044): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2044): [Launcher.java:1114:onPause()]onPause
D/KeyguardModel( 1497): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1497): createShortcutInfo...
D/ActionManagerService( 1916): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2780): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2044): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
I/[SystemUI]QSlideListController( 1497): onReceive = android.intent.action.PACKAGE_REMOVED
V/BoardContentProvider( 2780): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/KeyguardModel( 1497): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1497): createShortcutInfo...
I/GBoardWebViewUtils( 2044): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2044): , create_time: 1430558575574
I/GBoardWebViewUtils( 2044): , expire_time: 0
I/GBoardWebViewUtils( 2044): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2044): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2044): , display: false
I/GBoardWebViewUtils( 2044): , animation: false }
I/GBoardWebViewUtils( 2044): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2044): , create_time: 1430558575600
I/GBoardWebViewUtils( 2044): , expire_time: 0
I/GBoardWebViewUtils( 2044): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2044): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2044): , display: false
I/GBoardWebViewUtils( 2044): , animation: false }
I/GBoardWebViewUtils( 2044): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1455195784986
I/GBoardWebViewUtils( 2044): , create_time: 1455195785688
I/GBoardWebViewUtils( 2044): , expire_time: 0
I/GBoardWebViewUtils( 2044): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2044): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2044): , display: false
I/GBoardWebViewUtils( 2044): , animation: false }
D/WindowManager( 1057): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
W/ResourceType( 1497): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1497): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/SystemUI[Framework]( 1057): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx( 1057): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1057): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1057): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1057): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d3d78fb,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1057): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1497): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1497): createShortcutInfo...
D/InputDispatcher( 1057): Focus entered window: Window{24724994 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/WallpaperManager( 2044): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/SplitUIManager( 1879): split_name #11 / not available #0
D/SplitUIService( 1879): removed split : 
W/ResourceType( 1497): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1497): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]GBoardWebView( 2044): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/KeyguardModel( 1497): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1497): createShortcutInfo...
W/ResourceType( 1497): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1497): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1497): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1497): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[SystemUI]NavigationThemeResource( 1497): notify navigation bar color(0x0)
I/[SystemUI]NavigationThemeResource( 1497): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1497):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1497): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardModel( 1497): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1497): createShortcutInfo...
D/KeyguardModel( 1497): handleShortcutListChanged...
D/KeyguardModel( 1497): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1497): createShortcutInfo...
I/art     ( 1057): Explicit concurrent mark sweep GC freed 26722(1628KB) AllocSpace objects, 9(528KB) LOS objects, 33% free, 44MB/66MB, paused 1.729ms total 163.361ms
I/art     ( 1057): WaitForGcToComplete blocked for 154.545ms for cause Explicit
V/SIM_STK ( 1057): Menu title from STK is T-Mobile
D/KeyguardModel( 1497): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1497): createShortcutInfo...
W/ResourceType( 1497): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1497): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1497): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1497): createShortcutInfo...
W/ResourceType( 1497): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1497): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1497): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1497): createShortcutInfo...
D/SplitUIManager( 1879): split_name #11 / not available #0
I/SplitUIService( 1879): split app #11
W/ResourceType( 1497): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1497): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1497): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1497): createShortcutInfo...
V/SIM_STK ( 1057): Menu title from STK is T-Mobile
V/SIM_STK ( 1057): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2044): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1497): handleShortcutListChanged...
I/[LGHome]EVENT( 2044): [Launcher.java:5349:onStop()]onStop
I/[LGHome]EVENT( 2044): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 2044): [setNavigationBarColor] color=0x 0
D/[Concierge]WidgetView( 2044): notifyExtViewAvailable
D/InputMethodManagerService( 1057): setImestate : 0
W/InputMethodManagerService( 1057): Got RemoteException sending setActive(false) notification to pid 6112 uid 10311
W/ResourcesManager( 6749): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/administrator( 1057): Handling package changes for user 0
D/PluginManager( 6749): init()
W/ActivityManager( 1057): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3793): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3793): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3793): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3793): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3793): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3793): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3793): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3793): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3793): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3793): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3793): [BTUI] [-] updateMediaPlayerInfo
I/[LGHome]Launcher.Model( 2044): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2044): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
V/SIM_STK ( 1057): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2044): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2044): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2044): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2044): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 2044): getTextBeforeCursor on inactive InputConnection
E/b       ( 1729): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]Launcher.Model( 2044): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2044): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 1057): Timeline: Activity_windows_visible id: ActivityRecord{3e6c7a2f u0 com.lge.launcher2/.Launcher t3} time:1291068
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2044): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2044): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2044): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2044): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2044): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2044): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2633): onStartCommand(). Type : 8
D/[Concierge]Service( 2633): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
I/NotificationService( 1057): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/[Concierge]Service( 2633): Update widget ID : 11
D/BackupManagerService( 1057): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/[Concierge]WidgetView( 2044): change position of spinner
D/JobSchedulerService( 1057): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1057): removeObsoleteFile: deleting file=4_task.xml
I/[Concierge]WidgetView( 2044): initWebView(). Time : 1457093673889
D/[Concierge]Service( 2633): onStartCommand(). Type : 0
I/[Concierge]WebView( 2044): Return exist ConciergeWebView. Reuse : 414891391
D/[Concierge]WidgetView( 2044): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2044): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2044): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@367f6e3c
I/[LGHome]EVENT( 2044): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2044): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2044): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2044): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2044): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2044): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2044): Widget kill message received. Destory myself. My : 1457092411341, New one : 1457093673889
D/[Concierge]WidgetView( 2044): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2044): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/IInputConnectionWrapper( 2044): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher( 2044): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2044): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2044): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2044): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2044): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2044): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2044): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2044): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2044): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2044): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2044): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2044): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Thermal-Lib( 3179): Thermal-Lib-Client: Client request sent
I/ThermalEngine(  327): Thermal-Server: Thermal received msg from  override
I/art     ( 1057): Explicit concurrent mark sweep GC freed 10796(583KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 44MB/66MB, paused 2.475ms total 296.557ms
I/Timeline( 2044): Timeline: Activity_idle id: android.os.BinderProxy@103f5855 time:1291211
W/ResourcesManager( 1057): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1057): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2044): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/AndroidRuntime( 6718): Shutting down VM
W/ExternalStrings( 6749): load override strings
W/ExternalStrings( 6749): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6749): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6749): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6749): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6749): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6749): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6749): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6749): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6749): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6749): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6749): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6749): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6749): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6749): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6749): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6749): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6749): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6749): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 6749): onCreate
V/Signer  ( 6749): override build config not found
D/Signer  ( 6749): value of property debug is false
I/chromium( 2044): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
D/LGMDMWrapper( 6749): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6749): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6749): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6749): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6749): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6749): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6749): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6749): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6749): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6749): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6749): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6749): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6749): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 6749): Create singleton instance
I/GBoardtInterface( 2044): onReloaded()
I/GBoardWebViewClient( 2044): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2780): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2780): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1916): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2780): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2780): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1916): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2780): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2780): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2780): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2780): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2780): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2044): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2044): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2044): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2044): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2044): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2044): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LGMDMWrapper( 6749): LG MDM library v4.0.0 is available on this device.
D/PostponalbeReceiver( 6749): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/ContextImpl( 6749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/AppUp4:PreloadHelper( 5710): added Exclude : com.test.thalitest
I/ActivityManager( 1057): Killing 6014:com.lge.bnr/1000 (adj 15): empty #17
W/ActivityThread( 6749): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/libprocessgroup( 1057): failed to open /acct/uid_1000/pid_6014/cgroup.procs: No such file or directory
D/VoicemailCleanupService( 2353): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1057): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6786 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     (  337): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 201us total 12.312ms
I/art     (  337): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 9.432ms
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 16.909ms
E/SQLiteLog( 2353): (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 2353): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 2353): Process: android.process.acore, PID: 2353
E/AndroidRuntime( 2353): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2353): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2353): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/AndroidRuntime( 2353): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 2353): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2353): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/AndroidRuntime( 2353): 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
E/AndroidRuntime( 2353): 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
E/AndroidRuntime( 2353): 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
E/AndroidRuntime( 2353): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 2353): 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
E/AndroidRuntime( 2353): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 2353): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 2353): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2353): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2353): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2353): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 2353): Sending signal. PID: 2353 SIG: 9
E/DropBoxManagerService( 1057): Can't write: system_app_crash
E/DropBoxManagerService( 1057): java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1057): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1057): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1057): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1057): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1057): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1057): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1057): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1057): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1057): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1057): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1057): 	... 5 more
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6749): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteOpenHelper( 6749): Couldn't open lockedapplications for writing (will try read-only):
E/SQLiteOpenHelper( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteOpenHelper( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 6749): 	at com.mcafee.d.c.run(Unknown Source)
I/GBoardtInterface( 2044): exportHTML()
W/SQLiteOpenHelper( 6749): Opened lockedapplications in read-only mode
I/GBoardtInterface( 2044): exportHTML()
I/ActivityManager( 1057): Process android.process.acore (pid 2353) has died
W/ActivityManager( 1057): Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 1000ms
W/ActivityManager( 1057): Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
W/ResourcesManager( 6786): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6786): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6786): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6786): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.notificationtray.e.<init>(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.notificationtray.e.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.notificationtray.NotificationComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
I/GBoardtInterface( 2044): exportHTML()
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.c2dm.a.d(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.c2dm.a.c(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.notification.g.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
D/LgDataFeature( 6749): LgDataFeature() Constructor: none
D/LgDataFeature( 6749): LgDataFeature() Constructor Done, null
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.J(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.c2dm.a.d(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.c2dm.a.c(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.notification.g.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.r(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.notification.c.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.notification.r.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6786): Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
E/SQLiteDatabase( 6786): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6786): 	a,t android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6786): 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
E/SQLiteDatabase( 6786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 6786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 6786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6786): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 6786): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6786): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6786): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 6786): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/System.err( 6786): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
W/System.err( 6786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
W/System.err( 6786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 6786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 6786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 6786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
W/System.err( 6786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
W/System.err( 6786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
W/System.err( 6786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
W/System.err( 6786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/System.err( 6786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 6786): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 6786): 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
W/System.err( 6786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 6786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 6786): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
W/System.err( 6786): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/System.err( 6786): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/System.err( 6786): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/System.err( 6786): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/System.err( 6786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6786): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6786): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6786): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6786): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6786): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6786): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.notification.o.d(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.notificationtray.a.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.notificationtray.a.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.notificationtray.a.c.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.notification.q.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.aq(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.MSSComponentConfig.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6786): Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
E/SQLiteDatabase( 6786): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6786): 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
E/SQLiteDatabase( 6786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 6786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 6786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6786): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 6786): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6786): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6786): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 6786): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/AndroidRuntime( 6786): Shutting down VM
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.MSSComponentConfig.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
E/AndroidRuntime( 6786): FATAL EXCEPTION: main
E/AndroidRuntime( 6786): Process: com.lge.email, PID: 6786
E/AndroidRuntime( 6786): java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6786): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
E/AndroidRuntime( 6786): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/AndroidRuntime( 6786): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/AndroidRuntime( 6786): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 6786): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/AndroidRuntime( 6786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6786): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6786): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/AndroidRuntime( 6786): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6786): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6786): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/AndroidRuntime( 6786): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/AndroidRuntime( 6786): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 6786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/AndroidRuntime( 6786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6786): 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
E/AndroidRuntime( 6786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 6786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 6786): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/AndroidRuntime( 6786): 	... 11 more
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.e(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6749): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.N(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6749): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6749): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6749): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6749): 	at com.mcafee.d.c.run(Unknown Source)
I/Process ( 6786): Sending signal. PID: 6786 SIG: 9
E/DropBoxManagerService( 1057): Can't write: system_app_crash
E/DropBoxManagerService( 1057): java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1057): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1057): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1057): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1057): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1057): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1057): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1057): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1057): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1057): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1057): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1057): 	... 5 more
W/ContextImpl( 6749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 

```
