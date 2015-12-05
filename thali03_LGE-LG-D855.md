#### Test 50388019f33194e_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/UEI.SmartControl( 5858): Internal timer expired: 1
D/UEI.SmartControl( 5858): unbind internal service
,D/serial_port( 5858): close(fd = 25)
I/UEI.SmartControl( 5858): Serial port is closed.
D/AndroidRuntime( 5918): 
D/AndroidRuntime( 5918): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5918): CheckJNI is OFF
D/AndroidRuntime( 5918): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1915): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{138a1e87 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{138a1e87 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  345): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5933 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5918): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1824): Display #0 changed.
D/SplitWindowPolicy( 1915): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1915): topRunningActivity=ActivityInfo{23944829 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1915): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1915): topRunningActivity=ActivityInfo{cd567ae co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 5933): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/WebViewFactory( 5933): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 5933): Loading: webviewchromium
I/LibraryLoader( 5933): Time to load native libraries: 3 ms (timestamps 6993-6996)
,I/LibraryLoader( 5933): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5933): Binding Chromium to main looper Looper (main, tid 1) {ff64eea}
I/LibraryLoader( 5933): Expected native library version number "",actual native library version number ""
I/chromium( 5933): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5933): Initializing chromium process, renderers=0
W/art     ( 5933): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5933): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  326): registerClient() client 0xb1184f60, uid 10318
W/chromium( 5933): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5933): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5933): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34daaed9:true
,D/BluetoothAdapter( 5933): 182916571: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 5933): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5933): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5933): Build Date: 12/12/14 금
I/Adreno-EGL( 5933): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5933): Remote Branch: 
I/Adreno-EGL( 5933): Local Patches: 
I/Adreno-EGL( 5933): Reconstruct Branch: 
,W/chromium( 5933): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 5933): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5933): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5933): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5933): CordovaWebView is running on device made by: LGE
,W/art     ( 5933): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5933): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager( 1037): Killing 5465:com.lge.email/u0a23 (adj 15): empty #17
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 77333926118; DSPS: 2674707; Offset : -4307224675
,D/LgDataFeature( 5933): LgDataFeature() Constructor: none
,D/LgDataFeature( 5933): LgDataFeature() Constructor Done, null
W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_5465/cgroup.procs: No such file or directory
W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{a8651b4 u0 com.example.hello/.MainActivity t4}
,D/OpenGLRenderer( 5933): Render dirty regions requested: true
I/OpenGLRenderer( 5933): Initialized EGL, version 1.4
D/OpenGLRenderer( 5933): Enabling debug mode 0
,D/Atlas   ( 5933): Validating map...
,D/SplitWindow( 1037): check instance of lgWin Window{14ec328b u0 com.example.hello/com.example.hello.MainActivity}
,I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1445): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1445): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1445):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1445): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@6d283de,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1037): Displayed com.example.hello/.MainActivity: +669ms (total +766ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{a8651b4 u0 com.example.hello/.MainActivity t4} time:77512
,I/Timeline( 5933): Timeline: Activity_idle id: android.os.BinderProxy@2f152bcb time:77518
I/chromium( 5933): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 5933): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium( 5933): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5933): 
,D/JsMessageQueue( 5933): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 5933): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5933): 
,E/GBMv2   (  345): DFP En is all cleared set to be enabled
E/GBMv2   (  345): Set value is all cleared set the max
I/GBMv2   (  345): DFP Enabled. Ignore VFP set
,D/jxcore_app_log( 5933): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435207936
D/JX-Cordova( 5933): jxcore cordova android initializing
,W/jxcore-log( 5933): Initializing JXcore engine
,W/jxcore-log( 5933): JXcore engine is ready
,W/jxcore-log( 5933): Starting JXcore engine
,W/m.example.hello( 5933): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[7522]" dev="sockfs" ino=7522 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 5933): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/m.example.hello( 5933): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10453]" dev="sockfs" ino=10453 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 5933): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,W/m.example.hello( 5933): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[29120]" dev="sockfs" ino=29120 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 5933): Platform android
W/jxcore-log( 5933): 
,W/jxcore-log( 5933): Process ARCH arm
W/jxcore-log( 5933): 
,I/jxcore-log( 5933): JXcore Cordova bridge is ready!
I/jxcore-log( 5933): 
,W/jxcore-log( 5933): JXcore engine is started
E/jxcore-log( 5933): >> LGE-LG-D855
E/jxcore-log( 5933): 
,I/jxcore-log( 5933): Total memory 2995761152
I/jxcore-log( 5933): 
I/jxcore-log( 5933): Free memory 653778944
I/jxcore-log( 5933): 
I/jxcore-log( 5933): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5933): 
I/jxcore-log( 5933): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5933): 
I/jxcore-log( 5933): userPath [ 'www' ]
I/jxcore-log( 5933): 
I/jxcore-log( 5933): Size 1440 2392
I/jxcore-log( 5933): 
,I/jxcore-log( 5933): Screen Brightness 50
I/jxcore-log( 5933): 
E/jxcore-log( 5933): Dummy Error Log.
E/jxcore-log( 5933): 
I/jxcore-log( 5933): getBuffer is called!!!!
I/jxcore-log( 5933): 
,D/InitAlarmsService( 4803): Clearing and rescheduling alarms.
,I/ActivityManager( 1037): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6020 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 6020): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6020): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3ba2e2de
,D/CalendarProvider2( 6020): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6020): Created com.android.providers.calendar.CalendarAlarmManager@ae715db(com.android.providers.calendar.CalendarProvider2@3ba2e2de)
,D/CalendarProvider2( 6020): Scheduling check of next Alarm
D/CalendarProvider2( 6020): SCHEDULE_ALARM_REMOVE
,I/ActivityManager( 1037): Killing 4803:com.android.calendar/u0a13 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10013/pid_4803/cgroup.procs: No such file or directory
,I/[SystemUI]QPairHandler( 1445): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1843): replaced split : contains_com.google.android.talk / true
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1445): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1445): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
D/SplitUIManager( 1843): split_name #11 / not available #0
I/SplitUIService( 1843): split app #11
,I/AppUp4:CustModeStarterReceiver( 5424): onReceive
,D/AppUp4:CustFacade( 5424): Context : android.app.ReceiverRestrictedContext@362f96d5
D/AppUp4:CustFacade( 5424): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5424): isPhone : true
D/AppUp4:CustModeStarterReceiver( 5424): begin check event
I/AppUp4:CustModeStarterReceiver( 5424): Event For Nothing, skip.
D/administrator( 1037): Handling package changes for user 0
,I/UpdateIcingCorporaServi( 4163): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,D/LockScreenSettings( 5589): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5589): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5589): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5589): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5589): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 5589): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
I/[LGHome]EVENT( 2007): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/art     ( 2007): WaitForGcToComplete blocked for 8.527ms for cause DisableMovingGc
D/PackageBroadcastService( 2287): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PeopleContactsSync( 2287): CP2 sync disabled
,I/ActivityManager( 1037): Waited long enough for: ServiceRecord{366616e1 u0 com.google.android.music/.wear.WearMetadataSyncService}
W/ResourcesManager( 2007): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/[LGHome]Launcher( 2007): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 4163): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService( 1037): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/UpdateIcingCorporaServi( 4163): UpdateCorporaTask done [took 80 ms] updated apps [took 80 ms] 
W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2007): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/CalendarProvider2( 6020): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6020): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager( 1037): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6079 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1037): Killing 5127:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_5127/cgroup.procs: No such file or directory
,W/ResourcesManager( 6079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6079): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6079): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6079): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@12a0af8c, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@362f96d5, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@ff64eea, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@ae715db, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@f6f3878, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1a5fcb51, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3c626fb6, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@10b734b7, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2c9b6424, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2e84cb8d, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@9dd142, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@34006553, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@343c9e90, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@297f9389, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2f3bbf8e, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@6a203af, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@387513bc, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3544df45, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1eb8469a, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2f152bcb, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@295dafa8, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2c592ac1, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1f443266, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3848b9a7, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1db21e54, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@330cb1fd, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1510ef2, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@33d4943, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3a3ccbc0, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@287770f9, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@38dd283e, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3661369f, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2402e3ec, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2b3523b5, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@297f8a4a, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@6ac9dbb, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@293052d8, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2de14631, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@27340116, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@367d5a97, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@cc3c484, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1753146d
D/GeneralP,referenceUtils( 6079): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6079): [init]
,I/Config  ( 6079): LGCalendar ver.4.40.16
I/Config  ( 6079): start check model
I/Config  ( 6079): start check native_ca
I/Config  ( 6079): Config Operator=OPEN, Country=EU
D/Config  ( 6079): [setDefaultValuesToPref]
D/Config  ( 6079): [parseProfiles]
D/ProfilesParser( 6079): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6079): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6079): [updateProfiletoCountryInfo]
D/GeneralPreference( 6079): [checkAndMigrateOldPreference]
,D/AlertReceiver( 6079): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6079): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6079): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6079): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6079): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,I/AlertUtils( 6079): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6079): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6079): onHandleIntent
,D/HolidayDataLoader( 6079): readJsonAsset : holiday.json
D/AlertService( 6079): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6079): [updateWidgets] 
D/MonthWidgetProvider( 6079): [onReceive]
D/CalendarWidgetProvider( 6079): [onReceive]
,D/CalendarWidgetProvider( 6079): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6079): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6079): [onReceive]
D/CalendarWidgetProvider( 6079): [onReceive]
D/CalendarWidgetProvider( 6079): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6079): [onCreate] mContext.getPackageName() = com.android.calendar
,E/HolidayIntentService( 6079): onHandleIntent:holiday data empty
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService( 1037): Message: 2
D/WifiService( 1037): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1037): setWifiEnabled: false pid=5933, uid=10318, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1037): setWifiEnabled: false pid=5933, uid=10318
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 5933): ****TEST TOOK:  5068  ms ****
I/jxcore-log( 5933): 
I/jxcore-log( 5933): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5933): 
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=736545948, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2044d6a5 type 2 when 86440 com.android.providers.calendar} when 86440
D/[Concierge]Service( 2609): onStartCommand(). Type : 9
D/CalendarProviderBroadcastReceiver( 6020): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6020): [IntentService] WakeLock acquire, start IntentSerivce
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=736545948 [*alarm*], flags=0x0
D/CalendarProvider2( 6020): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6020): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6020): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6020): (284) automatic index on view_events(_id)
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{13e21688 type 0 when 1449275295145 com.android.vending} when 1449275295145
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CalendarProvider2( 6020): [IntentService] Release Lock
D/CalendarProvider2( 6020): CalendarProviderIntentService.onDestroy()
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/art     ( 2044): Explicit concurrent mark sweep GC freed 16701(905KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.483ms total 64.001ms
,V/GLSActivity( 2044): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2044): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2044): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2044): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2044): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2044): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5679): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5679): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5679): [1] 5.onFinished: Scheduling replication attempt 1.
D/AndroidRuntime( 6143): 
D/AndroidRuntime( 6143): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6143): CheckJNI is OFF
D/AndroidRuntime( 6143): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
,I/ActivityManager( 1037): Killing 5933:com.example.hello/u0a318 (adj 0): stop com.example.hello
I/WindowState( 1037): WIN DEATH: Window{14ec328b u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1037): Client connection lost with reason: 4
D/InputDispatcher( 1037): Window went away: Window{14ec328b u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings( 1037): Skipping PackageSetting{2caba069 com.test.thalitest/10311} due to missing metadata
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{a8651b4 u0 com.example.hello/.MainActivity t4}
,E/GBMv2   (  345): DFP En is all cleared set to be enabled
W/ActivityManager( 1037): Spurious death for ProcessRecord{3397d62a 5933:com.example.hello/u0a318}, curProc for 5933: null
,I/ActivityManager( 1037): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{a8651b4 u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{a8651b4 u0 com.example.hello/.MainActivity t4 f}
,I/[LGHome]EVENT( 2007): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2007): [Launcher.java:903:onResume()]onResume
,D/SplitWindowPolicy( 1915): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2007): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1915): topRunningActivity=ActivityInfo{2fde48dc co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]Launcher.Model( 2007): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/SplitWindowPolicy( 1915): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1915): topRunningActivity=ActivityInfo{12003de5 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]GBoardWebView( 2007): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
D/ActionManagerService( 1879): notifyUserLog: 1000003
W/GeofencerStateMachine( 1788): Ignoring removeGeofence because network location is disabled.
D/KeyguardModel( 1445): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,D/LIA_Informant_ActionManagerMessageHandler( 3551): handleMessage: what(1000) actionID(0x1000003)
D/LIA_Service_RemotePackageHandler( 1969): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
,D/LIA_MrGDBLogger_PackageInfoDetector( 3551): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
D/SplitUIManager( 1843): split_name #11 / not available #0
,D/SplitUIService( 1843): removed split : 
I/ActivityManager( 1037): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6179 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/System.err( 4115): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
I/[LGHome]LGActivityUtil( 2007): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2007): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1445): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2007): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1879): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2007): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 3551): handleMessage: what(1000) actionID(0x1000004)
D/KeyguardModel( 1445): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1445): createShortcutInfo...
V/BoardContentProvider( 3551): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/KeyguardModel( 1445): package = com.android.mms, class = com.android.mms.ui.ConversationList
I/GBoardWebViewUtils( 2007): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2007): , create_time: 1430558575574
I/GBoardWebViewUtils( 2007): , expire_time: 0
I/GBoardWebViewUtils( 2007): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2007): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2007): , display: false
I/GBoardWebViewUtils( 2007): , animation: false }
D/KeyguardModel( 1445): createShortcutInfo...
I/GBoardWebViewUtils( 2007): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2007): , create_time: 1430558575600
I/GBoardWebViewUtils( 2007): , expire_time: 0
I/GBoardWebViewUtils( 2007): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2007): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2007): , display: false
I/GBoardWebViewUtils( 2007): , animation: false }
I/GBoardWebViewUtils( 2007): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1449156806130
I/GBoardWebViewUtils( 2007): , create_time: 1449156807049
I/GBoardWebViewUtils( 2007): , expire_time: 0
I/GBoardWebViewUtils( 2007): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2007): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2007): , display: false
I/GBoardWebViewUtils( 2007): , animation: false }
W/System.err( 4115): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4115): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4115): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4115): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4115): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4115): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4115): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4115): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4115): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4115): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4115): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/WallpaperManager( 2007): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
D/SplitUIManager( 1843): split_name #11 / not available #0
I/SplitUIService( 1843): split app #11
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@6d283de,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1445): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1445): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 1445): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1445): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1445): createShortcutInfo...
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]GBoardWebView( 2007): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1445): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1445): createShortcutInfo...
W/ResourcesManager( 1445): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1445): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1445): createShortcutInfo...
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/KeyguardModel( 1445): handleShortcutListChanged...
D/KeyguardModel( 1445): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1445): createShortcutInfo...
I/art     ( 4163): Explicit concurrent mark sweep GC freed 7220(422KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 477us total 237.231ms
,D/KeyguardModel( 1445): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1445): createShortcutInfo...
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/art     ( 1037): Explicit concurrent mark sweep GC freed 24230(1567KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.468ms total 239.213ms
I/art     ( 1037): WaitForGcToComplete blocked for 242.654ms for cause Explicit
D/KeyguardModel( 1445): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1445): createShortcutInfo...
W/ResourcesManager( 6179): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1445): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1445): createShortcutInfo...
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1445): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1445): createShortcutInfo...
D/KeyguardModel( 1445): handleShortcutListChanged...
,D/PluginManager( 6179): init()
I/[LGHome]EVENT( 2007): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]EVENT( 2007): [Launcher.java:5349:onStop()]onStop
D/administrator( 1037): Handling package changes for user 0
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/[LGHome]Launcher.Model( 2007): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
,I/[LGHome]Launcher( 2007): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1445): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[LGHome]EVENT( 2007): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[SystemUI]NavigationThemeResource( 1445): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1445):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1445): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 2007): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2007): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2007): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{aed6580 u0 com.lge.launcher2/.Launcher t3} time:88098
I/[LGHome]Launcher.Model( 2007): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2007): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2007): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2007): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/AlertService( 6079): Beginning updateAlertNotification
,I/[LGHome]EVENT( 2007): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2007): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2007): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2007): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2609): onStartCommand(). Type : 8
D/[Concierge]Service( 2609): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,D/[Concierge]Service( 2609): Update widget ID : 11
D/[Concierge]WidgetView( 2007): change position of spinner
D/AlertService( 6079): No fired or scheduled alerts
I/[Concierge]WidgetView( 2007): initWebView(). Time : 1449275301129
D/[Concierge]Service( 2609): onStartCommand(). Type : 0
,I/[Concierge]WebView( 2007): Return exist ConciergeWebView. Reuse : 1061309918
,D/[Concierge]WidgetView( 2007): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2007): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2007): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3c021467
I/[LGHome]EVENT( 2007): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2007): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2007): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1037): Explicit concurrent mark sweep GC freed 10390(570KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.340ms total 271.413ms
I/[LGHome]EVENT( 2007): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2007): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2007): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
D/AlertService( 6079): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,W/[Concierge]WidgetView( 2007): Widget kill message received. Destory myself. My : 1449275241305, New one : 1449275301129
D/[Concierge]WidgetView( 2007): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2007): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2007): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2007): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2007): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2007): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2007): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
D/AlarmScheduler( 6079): No events found starting within 1 week.
I/[LGHome]EVENT( 2007): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2007): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2007): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1037): Killing 5527:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/AndroidRuntime( 6143): Shutting down VM
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2007): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2007): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2007): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2007): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2007): Timeline: Activity_idle id: android.os.BinderProxy@1c0dd905 time:88271
,W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_5527/cgroup.procs: No such file or directory,
,W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2007): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ExternalStrings( 6179): load override strings
W/ExternalStrings( 6179): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6179): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6179): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6179): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6179): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6179): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6179): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6179): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6179): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6179): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6179): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6179): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6179): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6179): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6179): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6179): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6179): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6179): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 6179): onCreate
V/Signer  ( 6179): override build config not found
D/Signer  ( 6179): value of property debug is false
,I/chromium( 2007): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,D/LGMDMWrapper( 6179): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6179): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6179): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6179): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6179): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6179): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6179): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,D/LGMDMWrapper( 6179): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6179): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6179): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6179): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6179): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6179): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 6179): Create singleton instance
,I/GBoardtInterface( 2007): onReloaded()
,I/GBoardWebViewClient( 2007): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3551): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3551): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1879): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 3551): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3551): onEvent() : ACTION_BOARD_ENABLED
D/LGMDMWrapper( 6179): LG MDM library v4.0.0 is available on this device.
D/ActionManagerService( 1879): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3551): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3551): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3551): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3551): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3551): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2007): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2007): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2007): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2007): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,D/GBoardUriUtils( 2007): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2007): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/PostponalbeReceiver( 6179): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,W/ContextImpl( 6179): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
E/SQLiteLog( 5424): (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
E/SQLiteDatabase( 5424): Error inserting package=com.example.hello
E/SQLiteDatabase( 5424): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5424): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5424): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
E/SQLiteDatabase( 5424): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 5424): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5424): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
E/SQLiteDatabase( 5424): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
E/SQLiteDatabase( 5424): 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
E/SQLiteDatabase( 5424): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 5424): 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
E/SQLiteDatabase( 5424): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
E/SQLiteDatabase( 5424): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
E/SQLiteDatabase( 5424): 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
E/SQLiteDatabase( 5424): 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
E/SQLiteDatabase( 5424): 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
E/SQLiteDatabase( 5424): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/SQLiteDatabase( 5424): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/SQLiteDatabase( 5424): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
E/SQLiteDatabase( 5424): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5424): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5424): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 5424): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5424): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5424): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 5424): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1037): Killing 5650:com.lge.eula/1000 (adj 15): empty #17
,I/qdhwcomposer(  282): handle_blank_event: dpy:0 panel power state: 0

```
