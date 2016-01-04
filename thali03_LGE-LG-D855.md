#### Test 50388019831b9e1_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 78079358685; DSPS: 2699353; Offset : -4309711777
,D/AndroidRuntime( 5926): 
D/AndroidRuntime( 5926): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5926): CheckJNI is OFF
--------- beginning of system
I/ActivityManager( 1033): Killing 5192:com.wsandroid.suite.lge/1000 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_5192/cgroup.procs: No such file or directory
D/AndroidRuntime( 5926): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1033): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1976): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1033): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1033): setTaskToReturnTo : TaskRecord{10164aad #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1033): setTaskToReturnTo : TaskRecord{10164aad #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1033): AppWindowTokenEx init.. 
E/GBMv2   (  352): DFP En is all cleared set to be enabled
I/ActivityManager( 1033): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5952 uid=10319 gids={50319, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5926): Shutting down VM
V/ActivityManager( 1033): Display changed displayId=0
D/DSDPConnection( 1868): Display #0 changed.
D/SplitWindowPolicy( 1976): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1976): topRunningActivity=ActivityInfo{257a9ca8 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1976): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1976): topRunningActivity=ActivityInfo{22e013c1 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 5952): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/WebViewFactory( 5952): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 5952): Loading: webviewchromium
,I/LibraryLoader( 5952): Time to load native libraries: 4 ms (timestamps 8952-8956)
I/LibraryLoader( 5952): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5952): Binding Chromium to main looper Looper (main, tid 1) {2fc849ed}
I/LibraryLoader( 5952): Expected native library version number "",actual native library version number ""
I/chromium( 5952): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5952): Initializing chromium process, renderers=0
,W/art     ( 5952): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5952): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  329): registerClient() client 0xb14fd7a0, uid 10319
,W/chromium( 5952): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5952): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5952): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1033): Message: 20
,D/BluetoothManagerService( 1033): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3eda89cf:true
D/BluetoothAdapter( 5952): 958128162: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 5952): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5952): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5952): Build Date: 12/12/14 금
I/Adreno-EGL( 5952): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5952): Remote Branch: 
I/Adreno-EGL( 5952): Local Patches: 
I/Adreno-EGL( 5952): Reconstruct Branch: 
,W/chromium( 5952): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 5952): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5952): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5952): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5952): CordovaWebView is running on device made by: LGE
,W/art     ( 5952): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5952): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5952): Render dirty regions requested: true
I/OpenGLRenderer( 5952): Initialized EGL, version 1.4
D/OpenGLRenderer( 5952): Enabling debug mode 0
,D/Atlas   ( 5952): Validating map...
D/SplitWindow( 1033): check instance of lgWin Window{35802351 u0 com.example.hello/com.example.hello.MainActivity}
,D/LgDataFeature( 5952): LgDataFeature() Constructor: none
,D/LgDataFeature( 5952): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1033): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1470): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1033): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1033): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1033): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@f7e28be,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1470): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1470):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1470): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1033): Displayed com.example.hello/.MainActivity: +626ms (total +710ms)
I/Timeline( 1033): Timeline: Activity_windows_visible id: ActivityRecord{130cb1e2 u0 com.example.hello/.MainActivity t4} time:79424
,I/Timeline( 5952): Timeline: Activity_idle id: android.os.BinderProxy@3a6095d2 time:79429
I/chromium( 5952): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 5952): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 5952): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 5952): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5952): 
,D/jxcore_app_log( 5952): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435332352
,D/JX-Cordova( 5952): jxcore cordova android initializing
E/GBMv2   (  352): DFP En is all cleared set to be enabled
E/GBMv2   (  352): Set value is all cleared set the max
I/GBMv2   (  352): DFP Enabled. Ignore VFP set
,W/jxcore-log( 5952): Initializing JXcore engine
,W/jxcore-log( 5952): JXcore engine is ready
,W/jxcore-log( 5952): Starting JXcore engine
,W/m.example.hello( 5952): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8351]" dev="sockfs" ino=8351 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 5952): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 5952): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10466]" dev="sockfs" ino=10466 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 5952): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/m.example.hello( 5952): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29491]" dev="sockfs" ino=29491 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 5952): Platform android
W/jxcore-log( 5952): 
W/jxcore-log( 5952): Process ARCH arm
W/jxcore-log( 5952): 
,I/jxcore-log( 5952): JXcore Cordova bridge is ready!
I/jxcore-log( 5952): 
W/jxcore-log( 5952): JXcore engine is started
,I/chromium( 5952): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5952): 
E/jxcore-log( 5952): >> LGE-LG-D855
E/jxcore-log( 5952): 
,I/jxcore-log( 5952): Total memory 2995761152
I/jxcore-log( 5952): 
I/jxcore-log( 5952): Free memory 654008320
I/jxcore-log( 5952): 
I/jxcore-log( 5952): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5952): 
I/jxcore-log( 5952): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5952): 
I/jxcore-log( 5952): userPath [ 'www' ]
I/jxcore-log( 5952): 
,I/jxcore-log( 5952): Size 1440 2392
I/jxcore-log( 5952): 
I/jxcore-log( 5952): Screen Brightness 50
I/jxcore-log( 5952): 
E/jxcore-log( 5952): Dummy Error Log.
E/jxcore-log( 5952): 
I/jxcore-log( 5952): getBuffer is called!!!!
I/jxcore-log( 5952): 
,D/InitAlarmsService( 4874): Clearing and rescheduling alarms.
,I/ActivityManager( 1033): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6009 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 6009): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6009): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@172623b1
,D/CalendarProvider2( 6009): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6009): Created com.android.providers.calendar.CalendarAlarmManager@391be022(com.android.providers.calendar.CalendarProvider2@172623b1)
D/CalendarProvider2( 6009): Scheduling check of next Alarm
D/CalendarProvider2( 6009): SCHEDULE_ALARM_REMOVE
,I/ActivityManager( 1033): Killing 4874:com.android.calendar/u0a13 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_10013/pid_4874/cgroup.procs: No such file or directory
,I/CalendarProvider2( 6009): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6009): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager( 1033): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6045 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1033): Killing 5606:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10061/pid_5606/cgroup.procs: No such file or directory
I/ActivityManager( 1033): Waited long enough for: ServiceRecord{1cfd602a u0 com.google.android.music/.wear.WearMetadataSyncService}
,W/ResourcesManager( 6045): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6045): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6045): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6045): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3bfb3417, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@349e6004, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2fc849ed, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@391be022, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@b74fab3, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1ea37870, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@30ec97e9, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@123bdc6e, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2bba8f0f, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2a9fab9c, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@22edc9a5, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2d4d517a, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@171b0d2b, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2ec9e588, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3f165b21, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@8cf0b46, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@13bb5107, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2bdbd234, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@2edc885d, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3a6095d2, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3b31f6a3, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@127ddda0, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2de4d59, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@200e3d1e, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1fe359ff, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@337333cc, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1d9d6615, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@1a5d0d2a, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2c1d971b, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@685c0b8, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@dfb4e91, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1b16d1f6, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@16f489f7, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@34323064, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@157542cd, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@14d61782, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@addce93, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@e13eed0, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@16203ec9, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@175229ce, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1a0cc0ef, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@22112
D/GeneralP,referenceUtils( 6045): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6045): [init]
,I/Config  ( 6045): LGCalendar ver.4.40.16
I/Config  ( 6045): start check model
I/Config  ( 6045): start check native_ca
I/Config  ( 6045): Config Operator=OPEN, Country=EU
D/Config  ( 6045): [setDefaultValuesToPref]
D/Config  ( 6045): [parseProfiles]
D/ProfilesParser( 6045): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6045): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6045): [updateProfiletoCountryInfo]
D/GeneralPreference( 6045): [checkAndMigrateOldPreference]
,D/AlertReceiver( 6045): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6045): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6045): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6045): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/art     ( 3265): Explicit concurrent mark sweep GC freed 3837(241KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 27MB/43MB, paused 637us total 42.219ms
,I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6045): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6045): set default noti to content://media/internal/audio/media/41
,I/InitNotificationRingtoneService( 6045): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6045): onHandleIntent
,D/HolidayDataLoader( 6045): readJsonAsset : holiday.json
E/AgendaWidgetManager( 6045): [updateWidgets] 
,D/AlertService( 6045): 0 Action = android.intent.action.PROVIDER_CHANGED
D/MonthWidgetProvider( 6045): [onReceive]
D/CalendarWidgetProvider( 6045): [onReceive]
D/CalendarWidgetProvider( 6045): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6045): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6045): [onReceive]
D/CalendarWidgetProvider( 6045): [onReceive]
D/CalendarWidgetProvider( 6045): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6045): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6045): onHandleIntent:holiday data empty
,D/BluetoothManagerService( 1033): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1033): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService( 1033): Message: 2
D/WifiService( 1033): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1033): setWifiEnabled: false pid=5952, uid=10319, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1033): setWifiEnabled: false pid=5952, uid=10319
E/WifiService( 1033): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 5952): ****TEST TOOK:  5073  ms ****
I/jxcore-log( 5952): 
I/jxcore-log( 5952): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5952): 
V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{1c3f82c1 type 2 when 87280 com.android.providers.calendar} when 87280
D/CalendarProviderBroadcastReceiver( 6009): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6009): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6009): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6009): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6009): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6009): (284) automatic index on view_events(_id)
V/AlarmManager( 1033): RTC_WAKEUP set : Alarm{1c2e5654 type 0 when 1451921683202 com.android.vending} when 1451921683202
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1033): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CalendarProvider2( 6009): [IntentService] Release Lock
D/CalendarProvider2( 6009): CalendarProviderIntentService.onDestroy()
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5745): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5745): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5745): [1] 5.onFinished: Scheduling replication attempt 1.
,D/AndroidRuntime( 6109): 
D/AndroidRuntime( 6109): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6109): CheckJNI is OFF
D/AndroidRuntime( 6109): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1033): Force stopping com.example.hello appid=10319 user=-1: uninstall pkg
,I/ActivityManager( 1033): Killing 5952:com.example.hello/u0a319 (adj 0): stop com.example.hello
I/WindowState( 1033): WIN DEATH: Window{35802351 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1033): Client connection lost with reason: 4
D/InputDispatcher( 1033): Window went away: Window{35802351 u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings( 1033): Skipping PackageSetting{1fde35e8 com.test.thalitest/10311} due to missing metadata
,D/AlertService( 6045): Beginning updateAlertNotification
,I/ActivityManager( 1033):   Force finishing activity ActivityRecord{130cb1e2 u0 com.example.hello/.MainActivity t4}
,E/GBMv2   (  352): DFP En is all cleared set to be enabled
,W/ActivityManager( 1033): Spurious death for ProcessRecord{26e57916 5952:com.example.hello/u0a319}, curProc for 5952: null
,I/ActivityManager( 1033): Force stopping com.example.hello appid=10319 user=0: pkg removed
I/ActivityManager( 1033):   Force finishing activity ActivityRecord{130cb1e2 u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager( 1033): Duplicate finish request for ActivityRecord{130cb1e2 u0 com.example.hello/.MainActivity t4 f}
,I/[LGHome]EVENT( 2092): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1976): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1976): topRunningActivity=ActivityInfo{27b36766 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2092): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1976): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1976): topRunningActivity=ActivityInfo{2fc84aa7 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/AlertService( 6045): No fired or scheduled alerts
I/[LGHome]EVENT( 2092): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2092): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1470): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Service_RemotePackageHandler( 2049): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
D/LIA_MrGDBLogger_PackageInfoDetector( 2697): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
,W/System.err( 4235): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 4235): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4235): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4235): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4235): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4235): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4235): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4235): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4235): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4235): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4235): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4235): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/GeofencerStateMachine( 1833): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1033): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1033): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6148 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/ActionManagerService( 1927): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2697): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2092): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[SystemUI]QSlideListController( 1470): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 2092): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2092): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2092): [Launcher.java:1114:onPause()]onPause
,I/[LGHome]GBoardWebView( 2092): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1927): notifyUserLog: 1000004
D/KeyguardModel( 1470): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1470): createShortcutInfo...
D/SplitUIManager( 1885): split_name #11 / not available #0
D/SplitUIService( 1885): removed split : 
,V/BoardContentProvider( 2697): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 2697): handleMessage: what(1000) actionID(0x1000004)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1470): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1470): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/GBoardWebViewUtils( 2092): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2092): , create_time: 1430558575574
I/GBoardWebViewUtils( 2092): , expire_time: 0
I/GBoardWebViewUtils( 2092): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2092): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2092): , display: false
I/GBoardWebViewUtils( 2092): , animation: false }
I/GBoardWebViewUtils( 2092): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2092): , create_time: 1430558575600
I/GBoardWebViewUtils( 2092): , expire_time: 0
I/GBoardWebViewUtils( 2092): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2092): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2092): , display: false
I/GBoardWebViewUtils( 2092): , animation: false }
I/GBoardWebViewUtils( 2092): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1451568242148
I/GBoardWebViewUtils( 2092): , create_time: 1451568243131
I/GBoardWebViewUtils( 2092): , expire_time: 0
I/GBoardWebViewUtils( 2092): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1451568242148&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2092): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2092): , display: false
I/GBoardWebViewUtils( 2092): , animation: false }
D/WallpaperManager( 2092): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/KeyguardModel( 1470): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1470): createShortcutInfo...
I/SystemUI[Framework]( 1033): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1033): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1033): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1033): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@f7e28be,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/art     ( 4285): Explicit concurrent mark sweep GC freed 15214(869KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 691us total 159.422ms
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2092): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2092): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/AlertService( 6045): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/SplitUIManager( 1885): split_name #11 / not available #0
I/SplitUIService( 1885): split app #11
D/KeyguardModel( 1470): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1470): createShortcutInfo...
I/art     ( 1033): Explicit concurrent mark sweep GC freed 15856(1109KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.755ms total 174.570ms
,W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/art     ( 1033): WaitForGcToComplete blocked for 172.632ms for cause Explicit
D/KeyguardModel( 1470): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1470): createShortcutInfo...
W/ResourcesManager( 1470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1470): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1470): createShortcutInfo...
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,D/KeyguardModel( 1470): handleShortcutListChanged...
D/KeyguardModel( 1470): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1470): createShortcutInfo...
W/ResourcesManager( 6148): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2092): [Launcher.java:5349:onStop()]onStop
,D/PluginManager( 6148): init()
D/KeyguardModel( 1470): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1470): createShortcutInfo...
,W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1470): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1470): createShortcutInfo...
D/administrator( 1033): Handling package changes for user 0
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1470): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1470): createShortcutInfo...
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/AlarmScheduler( 6045): No events found starting within 1 week.
D/KeyguardModel( 1470): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1470): createShortcutInfo...
I/ActivityManager( 1033): Killing 5720:com.lge.eula/1000 (adj 15): empty #17
,I/[LGHome]Launcher.Model( 2092): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2092): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2092): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2092): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2092): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2092): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2092): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2092): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2092): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2092): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/NotificationService( 1033): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1033): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1033): Receieved: android.intent.action.PACKAGE_REMOVED
,V/SIM_STK ( 1033): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2092): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2092): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2092): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_5720/cgroup.procs: No such file or directory
D/KeyguardModel( 1470): handleShortcutListChanged...
D/PhoneStatusBar( 1470): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1470): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1470):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1470): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1033): removeObsoleteFile: deleting file=4_task.xml
,I/Timeline( 1033): Timeline: Activity_windows_visible id: ActivityRecord{38123c66 u0 com.lge.launcher2/.Launcher t3} time:89430
I/[Concierge]WidgetView( 2092): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2609): onStartCommand(). Type : 8
D/[Concierge]Service( 2609): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2609): Update widget ID : 11
,D/[Concierge]WidgetView( 2092): change position of spinner
I/[Concierge]WidgetView( 2092): initWebView(). Time : 1451921689243
D/[Concierge]Service( 2609): onStartCommand(). Type : 0
,I/[Concierge]WebView( 2092): Return exist ConciergeWebView. Reuse : 483414226
,D/[Concierge]WidgetView( 2092): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2092): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2092): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3e3c6f8c
I/[LGHome]EVENT( 2092): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2092): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2092): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2092): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2092): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2092): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/ResourcesManager( 1033): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/[Concierge]WidgetView( 2092): Widget kill message received. Destory myself. My : 1451921628166, New one : 1451921689243
D/[Concierge]WidgetView( 2092): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2092): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2092): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2092): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2092): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2092): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,I/[LGHome]EVENT( 2092): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2092): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2092): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2092): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1033): Explicit concurrent mark sweep GC freed 8244(427KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.919ms total 275.527ms
I/[LgeWidgetLib]LgeAppWidgetHostView( 2092): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2092): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2092): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2092): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 1033): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Timeline( 2092): Timeline: Activity_idle id: android.os.BinderProxy@2648d2f4 time:89615
W/ResourceType( 1033): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2092): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/AndroidRuntime( 6109): Shutting down VM
,I/chromium( 2092): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,W/ExternalStrings( 6148): load override strings
W/ExternalStrings( 6148): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6148): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6148): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6148): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6148): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6148): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6148): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6148): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6148): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6148): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6148): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6148): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6148): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6148): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6148): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6148): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6148): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6148): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 6148): onCreate
I/GBoardtInterface( 2092): onReloaded()
,I/GBoardWebViewClient( 2092): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2697): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2697): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1927): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2697): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2697): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1927): notifyUserLog: 1000001
V/BoardContentProvider( 2697): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 2697): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2697): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2697): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2697): onSettingEvent() : GBoard On - add scheduler - 0
V/Signer  ( 6148): override build config not found
D/Signer  ( 6148): value of property debug is false
D/GBoardUriUtils( 2092): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2092): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2092): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2092): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,D/GBoardUriUtils( 2092): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1451568242148&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2092): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1451568242148&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LGMDMWrapper( 6148): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 6148): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6148): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6148): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6148): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6148): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6148): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6148): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6148): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6148): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6148): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6148): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6148): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 6148): Create singleton instance
,D/LGMDMWrapper( 6148): LG MDM library v4.0.0 is available on this device.
,D/PostponalbeReceiver( 6148): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,W/ContextImpl( 6148): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
E/SQLiteLog( 5503): (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
E/SQLiteDatabase( 5503): Error inserting package=com.example.hello
E/SQLiteDatabase( 5503): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5503): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5503): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
E/SQLiteDatabase( 5503): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 5503): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5503): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
E/SQLiteDatabase( 5503): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
E/SQLiteDatabase( 5503): 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
E/SQLiteDatabase( 5503): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 5503): 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
E/SQLiteDatabase( 5503): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
E/SQLiteDatabase( 5503): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
E/SQLiteDatabase( 5503): 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
E/SQLiteDatabase( 5503): 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
E/SQLiteDatabase( 5503): 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
E/SQLiteDatabase( 5503): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/SQLiteDatabase( 5503): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/SQLiteDatabase( 5503): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
E/SQLiteDatabase( 5503): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5503): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5503): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 5503): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5503): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5503): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 5503): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1033): Killing 4818:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_4818/cgroup.procs: No such file or directory
,D/VoicemailCleanupService( 2189): Cleaning up data for package: com.example.hello

```
