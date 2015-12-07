#### Test 50242285e132180_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/UEI.SmartControl( 5824): Internal timer expired: 1
D/UEI.SmartControl( 5824): unbind internal service
,D/serial_port( 5824): close(fd = 25)
I/UEI.SmartControl( 5824): Serial port is closed.
D/AndroidRuntime( 5876): 
D/AndroidRuntime( 5876): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5876): CheckJNI is OFF
D/sensors_hal_Time( 1066): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1066): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1066): tsOffsetIs: Apps: 77790330652; DSPS: 2689851; Offset : -4313697461
D/AndroidRuntime( 5876): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1066): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1946): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1066): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1066): setTaskToReturnTo : TaskRecord{26056d4e #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1066): setTaskToReturnTo : TaskRecord{26056d4e #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1066): AppWindowTokenEx init.. 
E/GBMv2   (  335): DFP En is all cleared set to be enabled
I/ActivityManager( 1066): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5892 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5876): Shutting down VM
V/ActivityManager( 1066): Display changed displayId=0
D/DSDPConnection( 1850): Display #0 changed.
D/SplitWindowPolicy( 1946): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1946): topRunningActivity=ActivityInfo{24eae5a4 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1946): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1946): topRunningActivity=ActivityInfo{ad3ef0d co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 5892): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/ActivityManager( 1066): Killing 5475:com.lge.email/u0a23 (adj 15): empty #17
,I/WebViewFactory( 5892): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,W/libprocessgroup( 1066): failed to open /acct/uid_10023/pid_5475/cgroup.procs: No such file or directory
,I/LibraryLoader( 5892): Loading: webviewchromium
,I/LibraryLoader( 5892): Time to load native libraries: 6 ms (timestamps 8189-8195)
I/LibraryLoader( 5892): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5892): Binding Chromium to main looper Looper (main, tid 1) {1907d0f9}
,I/LibraryLoader( 5892): Expected native library version number "",actual native library version number ""
I/chromium( 5892): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5892): Initializing chromium process, renderers=0
,W/art     ( 5892): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5892): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  319): registerClient() client 0xb14fd520, uid 10318
W/chromium( 5892): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 5892): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5892): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1066): Message: 20
D/BluetoothManagerService( 1066): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e93ef68:true
D/BluetoothAdapter( 5892): 597035070: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 5892): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5892): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5892): Build Date: 12/12/14 금
I/Adreno-EGL( 5892): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5892): Remote Branch: 
I/Adreno-EGL( 5892): Local Patches: 
I/Adreno-EGL( 5892): Reconstruct Branch: 
,W/chromium( 5892): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 5892): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5892): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5892): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5892): CordovaWebView is running on device made by: LGE
,W/art     ( 5892): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5892): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1066): Activity pause timeout for ActivityRecord{2ff17e6f u0 com.example.hello/.MainActivity t4}
,D/OpenGLRenderer( 5892): Render dirty regions requested: true
,I/OpenGLRenderer( 5892): Initialized EGL, version 1.4
D/OpenGLRenderer( 5892): Enabling debug mode 0
D/Atlas   ( 5892): Validating map...
,D/SplitWindow( 1066): check instance of lgWin Window{6494a62 u0 com.example.hello/com.example.hello.MainActivity}
,I/SystemUI[Framework]( 1066): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1441): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1441): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1441):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1441): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1066): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1066): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1066): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1066): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33601180,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1066): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/Timeline( 5892): Timeline: Activity_idle id: android.os.BinderProxy@1c72fcee time:78617
,D/LgDataFeature( 5892): LgDataFeature() Constructor: none
D/LgDataFeature( 5892): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1066): Displayed com.example.hello/.MainActivity: +627ms (total +720ms)
I/Timeline( 1066): Timeline: Activity_windows_visible id: ActivityRecord{2ff17e6f u0 com.example.hello/.MainActivity t4} time:78640
I/chromium( 5892): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 5892): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 5892): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5892): 
,D/JsMessageQueue( 5892): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 5892): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5892): 
,D/jxcore_app_log( 5892): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435341568
D/JX-Cordova( 5892): jxcore cordova android initializing
,W/jxcore-log( 5892): Initializing JXcore engine
,W/jxcore-log( 5892): JXcore engine is ready
,W/jxcore-log( 5892): Starting JXcore engine
W/m.example.hello( 5892): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[6057]" dev="sockfs" ino=6057 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 5892): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 5892): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10348]" dev="sockfs" ino=10348 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 5892): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/m.example.hello( 5892): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[28250]" dev="sockfs" ino=28250 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 5892): Platform android
W/jxcore-log( 5892): 
W/jxcore-log( 5892): Process ARCH arm
W/jxcore-log( 5892): 
,I/jxcore-log( 5892): JXcore Cordova bridge is ready!
I/jxcore-log( 5892): 
W/jxcore-log( 5892): JXcore engine is started
,E/jxcore-log( 5892): >> LGE-LG-D855
E/jxcore-log( 5892): 
I/jxcore-log( 5892): Total memory 2995761152
I/jxcore-log( 5892): 
I/jxcore-log( 5892): Free memory 662605824
I/jxcore-log( 5892): 
I/jxcore-log( 5892): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5892): 
I/jxcore-log( 5892): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5892): 
,I/jxcore-log( 5892): userPath [ 'www' ]
I/jxcore-log( 5892): 
I/jxcore-log( 5892): Size 1440 2392
I/jxcore-log( 5892): 
I/jxcore-log( 5892): Screen Brightness 50
I/jxcore-log( 5892): 
E/jxcore-log( 5892): Dummy Error Log.
E/jxcore-log( 5892): 
,E/GBMv2   (  335): DFP En is all cleared set to be enabled
E/GBMv2   (  335): Set value is all cleared set the max
I/GBMv2   (  335): DFP Enabled. Ignore VFP set
,I/jxcore-log( 5892): getBuffer is called!!!!
I/jxcore-log( 5892): 
,D/InitAlarmsService( 4821): Clearing and rescheduling alarms.
,I/ActivityManager( 1066): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5986 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 5986): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5986): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@195711fd
,D/CalendarProvider2( 5986): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5986): Created com.android.providers.calendar.CalendarAlarmManager@2396083e(com.android.providers.calendar.CalendarProvider2@195711fd)
D/CalendarProvider2( 5986): Scheduling check of next Alarm
,D/CalendarProvider2( 5986): SCHEDULE_ALARM_REMOVE
I/ActivityManager( 1066): Killing 4821:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1066): failed to open /acct/uid_10013/pid_4821/cgroup.procs: No such file or directory
,I/ActivityManager( 1066): Waited long enough for: ServiceRecord{2d1c32c7 u0 com.google.android.music/.wear.WearMetadataSyncService}
,I/CalendarProvider2( 5986): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5986): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager( 1066): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6021 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1066): Killing 5137:com.wsandroid.suite.lge/1000 (adj 15): empty #17
W/libprocessgroup( 1066): failed to open /acct/uid_1000/pid_5137/cgroup.procs: No such file or directory
W/ResourcesManager( 6021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CalendarApplication( 6021): CalendarApplication.onCreate()
D/PreferenceKeysParser( 6021): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6021): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@357ea943, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@b52abc0, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1907d0f9, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2396083e, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3b58969f, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2096c3ec, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@46b83b5, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@36e66a4a, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@13b9fdbb, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@b2232d8, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@141da631, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1428e116, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3700ba97, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@bf3a484, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@14f5746d, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2f49f8a2, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1b8c6933, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@134884f0, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1001ea69, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1c72fcee, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@341a658f, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@15c9001c, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3645c425, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3715f9fa, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@37e1cbab, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@8740208, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@c337da1, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2db9bbc6, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@106f7787, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2f4b36b4, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@10e952dd, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3e85ce52, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@9420523, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2abf0a20, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1d2d3fd9, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@308e7d9e, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1d25d07f, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2fdaa84c, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@36290095, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@15e0d5aa, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3d50f59b, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@172ff
D/GeneralPreferenceUtils( 6021): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6021): [init]
I/Config  ( 6021): LGCalendar ver.4.40.16
I/Config  ( 6021): start check model
I/Config  ( 6021): start check native_ca
I/Config  ( 6021): Config Operator=OPEN, Country=EU
D/Config  ( 6021): [setDefaultValuesToPref]
D/Config  ( 6021): [parseProfiles]
D/ProfilesParser( 6021): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6021): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6021): [updateProfiletoCountryInfo]
D/GeneralPreference( 6021): [checkAndMigrateOldPreference]
D/AlertReceiver( 6021): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6021): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6021): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6021): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6021): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6021): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6021): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6021): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6021): onHandleIntent
D/HolidayDataLoader( 6021): readJsonAsset : holiday.json
D/AlertService( 6021): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6021): [updateWidgets] 
D/MonthWidgetProvider( 6021): [onReceive]
D/CalendarWidgetProvider( 6021): [onReceive]
D/CalendarWidgetProvider( 6021): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6021): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6021): [onReceive]
D/CalendarWidgetProvider( 6021): [onReceive]
D/CalendarWidgetProvider( 6021): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6021): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6021): onHandleIntent:holiday data empty
,D/BluetoothManagerService( 1066): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1066): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService( 1066): Message: 2
D/WifiService( 1066): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1066): setWifiEnabled: false pid=5892, uid=10318, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1066): setWifiEnabled: false pid=5892, uid=10318
E/WifiService( 1066): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 5892): ****TEST TOOK:  5066  ms ****
I/jxcore-log( 5892): 
I/jxcore-log( 5892): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5892): 
,D/AndroidRuntime( 6062): 
D/AndroidRuntime( 6062): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6062): CheckJNI is OFF
D/AndroidRuntime( 6062): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1066): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1066): Killing 5892:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/WindowState( 1066): WIN DEATH: Window{6494a62 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1066): Client connection lost with reason: 4
D/InputDispatcher( 1066): Window went away: Window{6494a62 u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager( 1066):   Force finishing activity ActivityRecord{2ff17e6f u0 com.example.hello/.MainActivity t4}
,W/PackageSettings( 1066): Skipping PackageSetting{144882e4 com.test.thalitest/10311} due to missing metadata
,E/GBMv2   (  335): DFP En is all cleared set to be enabled
,W/ActivityManager( 1066): Spurious death for ProcessRecord{7dd1012 5892:com.example.hello/u0a318}, curProc for 5892: null
I/ActivityManager( 1066): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1066):   Force finishing activity ActivityRecord{2ff17e6f u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager( 1066): Duplicate finish request for ActivityRecord{2ff17e6f u0 com.example.hello/.MainActivity t4 f}
,I/[LGHome]EVENT( 2065): [Launcher.java:5338:onStart()]onStart
,D/SplitWindowPolicy( 1946): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1946): topRunningActivity=ActivityInfo{2020eec2 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2065): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1946): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1946): topRunningActivity=ActivityInfo{22d0f4d3 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2065): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1441): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1066): Reconfiguring input devices.  changes=0x00000010
,D/LIA_MrGDBLogger_PackageInfoDetector( 2712): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
D/LIA_Service_RemotePackageHandler( 2026): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
W/GeofencerStateMachine( 1815): Ignoring removeGeofence because network location is disabled.
W/System.err( 4188): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 4188): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4188): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4188): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
,W/System.err( 4188): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4188): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4188): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4188): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4188): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4188): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4188): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4188): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1066): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6091 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/[LGHome]GBoardWebView( 2065): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1901): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2712): handleMessage: what(1000) actionID(0x1000003)
I/[SystemUI]QSlideListController( 1441): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 2065): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 2065): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2065): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1901): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2065): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 2712): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2065): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2065): , create_time: 1430558575574
I/GBoardWebViewUtils( 2065): , expire_time: 0
I/GBoardWebViewUtils( 2065): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2065): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2065): , display: false
I/GBoardWebViewUtils( 2065): , animation: false }
I/GBoardWebViewUtils( 2065): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2065): , create_time: 1430558575600
I/GBoardWebViewUtils( 2065): , expire_time: 0
I/GBoardWebViewUtils( 2065): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2065): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2065): , display: false
I/GBoardWebViewUtils( 2065): , animation: false }
I/GBoardWebViewUtils( 2065): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1449156806130
I/GBoardWebViewUtils( 2065): , create_time: 1449156807049
I/GBoardWebViewUtils( 2065): , expire_time: 0
I/GBoardWebViewUtils( 2065): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2065): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2065): , display: false
I/GBoardWebViewUtils( 2065): , animation: false }
,D/KeyguardModel( 1441): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1441): createShortcutInfo...
D/KeyguardModel( 1441): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1441): createShortcutInfo...
V/SIM_STK ( 1066): Menu title from STK is T-Mobile
W/ResourcesManager( 1441): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1441): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1441): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1441): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/WallpaperManager( 2065): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
W/ResourceType( 1441): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1441): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/SystemUI[Framework]( 1066): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1441): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1441): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1441): createShortcutInfo...
D/KeyguardModel( 1441): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/PhoneWindowManagerEx( 1066): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1066): setLGSystemUiVisibility(0x0)
,D/StatusBarManagerServiceEx( 1066): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1066): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33601180,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1066): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[LGHome]EVENT( 2065): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2065): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourcesManager( 1441): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1441): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1441): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1441): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1441): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1441): createShortcutInfo...
W/ResourcesManager( 1441): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1441): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1441): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1441): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1441): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1441): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1441): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1441): createShortcutInfo...
I/art     ( 4229): Explicit concurrent mark sweep GC freed 15600(911KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 538us total 160.028ms
,D/KeyguardModel( 1441): handleShortcutListChanged...
D/KeyguardModel( 1441): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1441): createShortcutInfo...
,D/KeyguardModel( 1441): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1441): createShortcutInfo...
D/SplitUIManager( 1867): split_name #11 / not available #0
D/SplitUIService( 1867): removed split : 
W/ResourceType( 1441): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1441): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1441): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1441): createShortcutInfo...
W/ResourceType( 1441): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1441): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1441): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1441): createShortcutInfo...
,W/ResourceType( 1441): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1441): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1441): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1441): createShortcutInfo...
I/art     ( 1066): Explicit concurrent mark sweep GC freed 16650(1112KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 8.283ms total 223.479ms
W/ResourcesManager( 6091): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/art     ( 1066): WaitForGcToComplete blocked for 93.809ms for cause Explicit
,D/SplitUIManager( 1867): split_name #11 / not available #0
I/SplitUIService( 1867): split app #11
,D/KeyguardModel( 1441): handleShortcutListChanged...
I/[LGHome]EVENT( 2065): [Launcher.java:5349:onStop()]onStop
,D/administrator( 1066): Handling package changes for user 0
D/PluginManager( 6091): init()
,V/SIM_STK ( 1066): Menu title from STK is T-Mobile
,I/NotificationService( 1066): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1066): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1066): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister( 1066): removeObsoleteFile: deleting file=4_task.xml
I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
D/PhoneStatusBar( 1441): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
,I/[SystemUI]NavigationThemeResource( 1441): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1441):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1441): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2065): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2065): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/Timeline( 1066): Timeline: Activity_windows_visible id: ActivityRecord{1ce2d3c2 u0 com.lge.launcher2/.Launcher t3} time:85848
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/art     ( 1066): Explicit concurrent mark sweep GC freed 7449(437KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 10.378ms total 213.296ms
I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2065): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/[Concierge]Service( 2611): onStartCommand(). Type : 8
D/[Concierge]Service( 2611): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2611): Update widget ID : 11
D/[Concierge]WidgetView( 2065): change position of spinner
I/[Concierge]WidgetView( 2065): initWebView(). Time : 1449501153580
D/[Concierge]Service( 2611): onStartCommand(). Type : 0
,D/AndroidRuntime( 6062): Shutting down VM
,W/ResourcesManager( 1066): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[Concierge]WebView( 2065): Return exist ConciergeWebView. Reuse : 43997437
D/[Concierge]WidgetView( 2065): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2065): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/ResourceType( 1066): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LgeWidgetLib]ExtViewHost( 2065): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@d6e884f
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2065): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2065): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/[Concierge]WidgetView( 2065): Widget kill message received. Destory myself. My : 1449501096154, New one : 1449501153580
D/[Concierge]WidgetView( 2065): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2065): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2065): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2065): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2065): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2065): Timeline: Activity_idle id: android.os.BinderProxy@b04a1b0 time:86032
,W/ExternalStrings( 6091): load override strings
W/ExternalStrings( 6091): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6091): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6091): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6091): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6091): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6091): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6091): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6091): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6091): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6091): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6091): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6091): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6091): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6091): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6091): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6091): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6091): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6091): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 6091): onCreate
I/chromium( 2065): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
V/Signer  ( 6091): override build config not found
,D/Signer  ( 6091): value of property debug is false
I/GBoardtInterface( 2065): onReloaded()
I/GBoardWebViewClient( 2065): onPageFinished url:file:///android_asset/www/main.html
,V/BoardContentProvider( 2712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1901): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2712): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2712): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1901): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2712): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2712): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2712): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2712): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LGMDMWrapper( 6091): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6091): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/GBoardUriUtils( 2065): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2065): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/LGMDMWrapper( 6091): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6091): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6091): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/GBoardUriUtils( 2065): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2065): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2065): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2065): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LGMDMWrapper( 6091): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6091): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,D/LGMDMWrapper( 6091): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6091): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6091): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
,D/LGMDMWrapper( 6091): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6091): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6091): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 6091): Create singleton instance
,I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
