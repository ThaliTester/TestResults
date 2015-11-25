#### Test 503880196dc97cd_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 77403037888; DSPS: 2677201; Offset : -4313425804
,D/AndroidRuntime( 5913): 
D/AndroidRuntime( 5913): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5913): CheckJNI is OFF
D/AndroidRuntime( 5913): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1034): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1966): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1034): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
V/ActivityStackEx( 1034): create ActivityStackEx
D/ActivityManager( 1034): setTaskToReturnTo : TaskRecord{304ca418 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1034): setTaskToReturnTo : TaskRecord{304ca418 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1034): AppWindowTokenEx init.. 
E/GBMv2   (  343): DFP En is all cleared set to be enabled
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{253292c7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgeAbsQuickCoverView( 1415): mCoverXPos: 0 ,mCoverYPos: 0
D/LgeAbsQuickCoverView( 1415): mCoverWidth: 0 ,mCoverHeight: 0
I/ActivityManager( 1034): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5928 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5913): Shutting down VM
V/ActivityManager( 1034): Display changed displayId=0
D/DSDPConnection( 1868): Display #0 changed.
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{740bf84 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{3503f36d co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/ContextHelper( 5928): convertTheme. context->name=com.example.hello themeResourceId=16973833
,I/WebViewFactory( 5928): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 5928): Loading: webviewchromium
I/LibraryLoader( 5928): Time to load native libraries: 5 ms (timestamps 8527-8532)
I/LibraryLoader( 5928): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5928): Binding Chromium to main looper Looper (main, tid 1) {36d05359}
,I/LibraryLoader( 5928): Expected native library version number "",actual native library version number ""
I/chromium( 5928): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5928): Initializing chromium process, renderers=0
,W/art     ( 5928): Attempt to remove local handle scope entry from IRT, ignoring
D/UEI.SmartControl( 5851): Internal timer expired: 1
D/UEI.SmartControl( 5851): unbind internal service
D/UEI.SmartControl( 5851): Service.onUnbind: IControl
D/UEI.SmartControl( 5851): Service.onDestroy,
D/UEI.SmartControl( 5851): Lock is in USE false
D/UEI.SmartControl( 5851): unbind internal service
D/serial_port( 5851): close(fd = 25)
,I/UEI.SmartControl( 5851): Serial port is closed.
I/UEI.SmartControl( 5851): Serial port is closed.
D/UEI.SmartControl( 5851): Blaster closed
D/UEI.SmartControl( 5851): Shut down QS...
D/UEI.SmartControl( 5851): Stopping QS lib
D/UEI.SmartControl( 5851): QS lib stop result = true
D/UEI.SmartControl( 5851): Stopped QS lib
D/UEI.SmartControl( 5851): Stopped file observer...
,D/UEI.SmartControl( 5851): QS shutdown complete
W/chromium( 5928): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 5928): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5928): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5928): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,V/AudioPolicyService(  314): registerClient() client 0xb14fda00, uid 10318
D/BluetoothManagerService( 1034): Message: 20
,D/BluetoothManagerService( 1034): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@150edfe2:true
,I/Adreno-EGL( 5928): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5928): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5928): Build Date: 12/12/14 금
I/Adreno-EGL( 5928): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5928): Remote Branch: 
I/Adreno-EGL( 5928): Local Patches: 
I/Adreno-EGL( 5928): Reconstruct Branch: 
D/BluetoothAdapter( 5928): 535743262: getState() :  mService = null. Returning STATE_OFF
,W/chromium( 5928): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 5928): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5928): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5928): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5928): CordovaWebView is running on device made by: LGE
,W/art     ( 5928): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5928): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1034): Activity pause timeout for ActivityRecord{2d315e71 u0 com.example.hello/.MainActivity t2}
,D/OpenGLRenderer( 5928): Render dirty regions requested: true
,I/OpenGLRenderer( 5928): Initialized EGL, version 1.4
D/OpenGLRenderer( 5928): Enabling debug mode 0
D/Atlas   ( 5928): Validating map...
,D/SplitWindow( 1034): check instance of lgWin Window{27dc258c u0 com.example.hello/com.example.hello.MainActivity}
,D/LgDataFeature( 5928): LgDataFeature() Constructor: none
D/LgDataFeature( 5928): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1034): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1466): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
,W/PhoneWindowManagerEx( 1034): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1034): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1034): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1034): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@c33ac3e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1034): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1034): Displayed com.example.hello/.MainActivity: +713ms (total +848ms)
I/Timeline( 5928): Timeline: Activity_idle id: android.os.BinderProxy@2f7237ce time:79079
,I/Timeline( 1034): Timeline: Activity_windows_visible id: ActivityRecord{2d315e71 u0 com.example.hello/.MainActivity t2} time:79080
I/chromium( 5928): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 5928): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 5928): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5928): 
,D/JsMessageQueue( 5928): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 5928): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5928): 
,D/jxcore_app_log( 5928): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435323136
D/JX-Cordova( 5928): jxcore cordova android initializing
,W/jxcore-log( 5928): Initializing JXcore engine
W/jxcore-log( 5928): JXcore engine is ready
,W/jxcore-log( 5928): Starting JXcore engine
W/m.example.hello( 5928): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8601]" dev="sockfs" ino=8601 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 5928): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 5928): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7461]" dev="sockfs" ino=7461 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 5928): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,W/m.example.hello( 5928): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29193]" dev="sockfs" ino=29193 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,E/GBMv2   (  343): DFP En is all cleared set to be enabled
E/GBMv2   (  343): Set value is all cleared set the max
I/GBMv2   (  343): DFP Enabled. Ignore VFP set
,W/jxcore-log( 5928): Platform android
W/jxcore-log( 5928): 
W/jxcore-log( 5928): Process ARCH arm
W/jxcore-log( 5928): 
,I/jxcore-log( 5928): JXcore Cordova bridge is ready!
I/jxcore-log( 5928): 
W/jxcore-log( 5928): JXcore engine is started
,E/jxcore-log( 5928): >> LGE-LG-D855
E/jxcore-log( 5928): 
I/jxcore-log( 5928): Total memory 2995761152
I/jxcore-log( 5928): 
I/jxcore-log( 5928): Free memory 662192128
I/jxcore-log( 5928): 
I/jxcore-log( 5928): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5928): 
I/jxcore-log( 5928): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5928): 
,I/jxcore-log( 5928): userPath [ 'www' ]
I/jxcore-log( 5928): 
I/jxcore-log( 5928): Size 1440 2392
I/jxcore-log( 5928): 
I/jxcore-log( 5928): Screen Brightness 50
I/jxcore-log( 5928): 
E/jxcore-log( 5928): Dummy Error Log.
E/jxcore-log( 5928): 
I/ActivityManager( 1034): Killing 5435:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,I/jxcore-log( 5928): getBuffer is called!!!!
I/jxcore-log( 5928): 
,W/libprocessgroup( 1034): failed to open /acct/uid_10008/pid_5435/cgroup.procs: No such file or directory
,D/InitAlarmsService( 4801): Clearing and rescheduling alarms.
,I/ActivityManager( 1034): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6030 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 6030): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6030): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3d9a2e5d
,D/CalendarProvider2( 6030): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6030): Created com.android.providers.calendar.CalendarAlarmManager@1feecb1e(com.android.providers.calendar.CalendarProvider2@3d9a2e5d)
D/CalendarProvider2( 6030): Scheduling check of next Alarm
D/CalendarProvider2( 6030): SCHEDULE_ALARM_REMOVE
I/ActivityManager( 1034): Killing 4801:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10013/pid_4801/cgroup.procs: No such file or directory
,I/CalendarProvider2( 6030): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6030): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager( 1034): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6057 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1034): Killing 5498:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10023/pid_5498/cgroup.procs: No such file or directory
,W/ResourcesManager( 6057): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6057): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6057): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6057): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@28d70ca3, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@127c3ba0, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@36d05359, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1feecb1e, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@11c3cfff, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@17f971cc, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@5a9cc15, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@12b87b2a, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1a8f6d1b, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@31deb8, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1681491, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@8bb1ff6, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@29adbff7, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1f822e64, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@19e868cd, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@33714582, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2ef46493, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1165ccd0, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@259fc4c9, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2f7237ce, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@37f6b6ef, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2ba2e5fc, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1356e485, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@397e02da, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2e21d30b, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@383665e8, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3ba64401, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@284972a6, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1a9894e7, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@21fff894, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@e321f3d, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@370a1332, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@bcf9883, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2e0a00, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@16a67239, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2cc2307e, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@38e939df, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2c69c62c, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1572f8f5, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2c4cd68a, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3ed194fb, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@fc31918
D/GeneralP,referenceUtils( 6057): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6057): [init]
,I/Config  ( 6057): LGCalendar ver.4.40.16
I/Config  ( 6057): start check model
I/Config  ( 6057): start check native_ca
I/Config  ( 6057): Config Operator=OPEN, Country=EU
D/Config  ( 6057): [setDefaultValuesToPref]
D/Config  ( 6057): [parseProfiles]
D/ProfilesParser( 6057): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6057): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6057): [updateProfiletoCountryInfo]
,D/GeneralPreference( 6057): [checkAndMigrateOldPreference]
D/AlertReceiver( 6057): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6057): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6057): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6057): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6057): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6057): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,I/AlertUtils( 6057): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6057): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6057): onHandleIntent
,D/HolidayDataLoader( 6057): readJsonAsset : holiday.json
D/AlertService( 6057): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6057): [updateWidgets] 
D/MonthWidgetProvider( 6057): [onReceive]
D/CalendarWidgetProvider( 6057): [onReceive]
,D/CalendarWidgetProvider( 6057): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,D/CalendarTypeController( 6057): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6057): [onReceive]
D/CalendarWidgetProvider( 6057): [onReceive]
D/CalendarWidgetProvider( 6057): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 6057): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6057): onHandleIntent:holiday data empty
,D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1034): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService( 1034): Message: 2
D/WifiService( 1034): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1034): setWifiEnabled: false pid=5928, uid=10318, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1034): setWifiEnabled: false pid=5928, uid=10318
E/WifiService( 1034): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 5928): ****TEST TOOK:  5066  ms ****
I/jxcore-log( 5928): 
I/jxcore-log( 5928): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5928): 
I/ActivityManager( 1034): Waited long enough for: ServiceRecord{96a86c u0 com.google.android.music/.wear.WearMetadataSyncService}
,D/AndroidRuntime( 6110): 
D/AndroidRuntime( 6110): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6110): CheckJNI is OFF
D/AndroidRuntime( 6110): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1034): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1034): Killing 5928:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/WindowState( 1034): WIN DEATH: Window{27dc258c u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1034): Client connection lost with reason: 4
D/InputDispatcher( 1034): Window went away: Window{27dc258c u0 com.example.hello/com.example.hello.MainActivity}
,I/ActivityManager( 1034):   Force finishing activity ActivityRecord{2d315e71 u0 com.example.hello/.MainActivity t2}
,W/PackageSettings( 1034): Skipping PackageSetting{1d5c7cc4 com.test.thalitest/10311} due to missing metadata
,E/GBMv2   (  343): DFP En is all cleared set to be enabled
,W/ActivityManager( 1034): Spurious death for ProcessRecord{67a09bc 5928:com.example.hello/u0a318}, curProc for 5928: null
I/ActivityManager( 1034): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1034):   Force finishing activity ActivityRecord{2d315e71 u0 com.example.hello/.MainActivity t2 f}
W/ActivityManager( 1034): Duplicate finish request for ActivityRecord{2d315e71 u0 com.example.hello/.MainActivity t2 f}
,I/art     ( 4233): Explicit concurrent mark sweep GC freed 15500(907KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 732us total 44.425ms
,I/[LGHome]EVENT( 2085): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2085): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{3a280ba2 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{17e48033 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
D/SplitWindowManager( 1034): removeStackAndNeedHomeResume ActivityStack{34559d45 stackId=1, 0 tasks}
I/[LGHome]EVENT( 2085): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 2085): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1920): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2724): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2085): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/GeofencerStateMachine( 1833): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1034): Reconfiguring input devices.  changes=0x00000010
D/LIA_Service_RemotePackageHandler( 2042): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
D/LIA_MrGDBLogger_PackageInfoDetector( 2724): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
I/[LGHome]LGActivityUtil( 2085): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 2085): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2085): [Launcher.java:1114:onPause()]onPause
I/[LGHome]GBoardWebView( 2085): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
I/[SystemUI]QSlideListController( 1466): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
,D/ActionManagerService( 1920): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2724): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2724): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2085): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2085): , create_time: 1430558575574
I/GBoardWebViewUtils( 2085): , expire_time: 0
I/GBoardWebViewUtils( 2085): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2085): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2085): , display: false
I/GBoardWebViewUtils( 2085): , animation: false }
I/GBoardWebViewUtils( 2085): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2085): , create_time: 1430558575600
I/GBoardWebViewUtils( 2085): , expire_time: 0
I/GBoardWebViewUtils( 2085): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2085): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2085): , display: false
I/GBoardWebViewUtils( 2085): , animation: false }
D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
I/GBoardWebViewUtils( 2085): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1447937693376
I/GBoardWebViewUtils( 2085): , create_time: 1447937694406
I/GBoardWebViewUtils( 2085): , expire_time: 0
I/GBoardWebViewUtils( 2085): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1447937693376&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2085): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2085): , display: false
I/GBoardWebViewUtils( 2085): , animation: false }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1466): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/WallpaperManager( 2085): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
W/System.err( 4190): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/System.err( 4190): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4190): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4190): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4190): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4190): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4190): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4190): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4190): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4190): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4190): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4190): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/SystemUI[Framework]( 1034): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
D/KeyguardModel( 1466): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1466): createShortcutInfo...
W/PhoneWindowManagerEx( 1034): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1034): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1034): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1034): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@c33ac3e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1034): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,I/[LGHome]GBoardWebView( 2085): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/PostponalbeReceiver( 5112): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
D/SplitUIManager( 1886): split_name #11 / not available #0
D/SplitUIService( 1886): removed split : 
D/KeyguardModel( 1466): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1466): createShortcutInfo...
,W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1466): createShortcutInfo...
D/KeyguardModel( 1466): handleShortcutListChanged...
,D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
,W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/SplitUIManager( 1886): split_name #11 / not available #0
I/SplitUIService( 1886): split app #11
D/KeyguardModel( 1466): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1466): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1466): createShortcutInfo...
V/SIM_STK ( 1034): Menu title from STK is T-Mobile
I/art     ( 1034): Explicit concurrent mark sweep GC freed 13885(1035KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 2.176ms total 216.199ms
,D/KeyguardModel( 1466): handleShortcutListChanged...
I/art     ( 1034): WaitForGcToComplete blocked for 184.149ms for cause Explicit
D/AppUp4:PreloadHelper( 5455): added Exclude : com.example.hello
,I/[LGHome]EVENT( 2085): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/administrator( 1034): Handling package changes for user 0
,I/[LGHome]EVENT( 2085): [Launcher.java:5349:onStop()]onStop
,I/ActivityManager( 1034): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6147 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/VoicemailCleanupService( 2158): Cleaning up data for package: com.example.hello
,V/SIM_STK ( 1034): Menu title from STK is T-Mobile
W/ResourcesManager( 6147): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6147): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6147): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6147): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/NotificationService( 1034): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1034): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1034): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1034): removeObsoleteFile: deleting file=2_task.xml
D/PhoneStatusBar( 1466): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
,I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher.Model( 2085): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/Timeline( 1034): Timeline: Activity_windows_visible id: ActivityRecord{2c3a70a2 u0 com.lge.launcher2/.Launcher t1} time:86532
I/[LGHome]Launcher.Model( 2085): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2085): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2085): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2085): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/LGEmail ( 6147): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/ResourcesManager( 1034): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[Concierge]WidgetView( 2085): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2630): onStartCommand(). Type : 8
D/[Concierge]Service( 2630): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2630): Update widget ID : 11
,D/[Concierge]WidgetView( 2085): change position of spinner
D/LGEmail ( 6147): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
I/art     ( 1034): Explicit concurrent mark sweep GC freed 8580(456KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.391ms total 240.095ms
D/[Concierge]Service( 2630): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2085): initWebView(). Time : 1448460743875
,W/ResourceType( 1034): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/ResourceType( 6147): No package identifier when getting value for resource number 0x00000000
I/[Concierge]WebView( 2085): Return exist ConciergeWebView. Reuse : 570133081
D/[Concierge]WidgetView( 2085): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2085): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2085): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3b742fa7
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2085): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/AndroidRuntime( 6110): Shutting down VM
D/[Concierge]WidgetView( 2085): isWidgetUpdateSkippable ? true
,D/[Concierge]WidgetBroadcastReceiver( 2085): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
D/LgDataFeature( 6147): LgDataFeature() Constructor: none
D/LgDataFeature( 6147): LgDataFeature() Constructor Done, null
W/[Concierge]WidgetView( 2085): Widget kill message received. Destory myself. My : 1448460685521, New one : 1448460743875
D/[Concierge]WidgetView( 2085): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2085): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2085): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2085): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2085): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2085): Timeline: Activity_idle id: android.os.BinderProxy@158b628e time:86707
,I/PackageChangeReceiver( 6147): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager( 1034): Killing 5562:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,I/chromium( 2085): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,W/libprocessgroup( 1034): failed to open /acct/uid_10061/pid_5562/cgroup.procs: No such file or directory
,D/LIA_Service_NativeEventReceiver( 2042): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
I/LIA_Service_PlatformUtil( 2042): startLIAService() : Trying to start LIA service ...
D/LIA_Service_LIAService( 2042): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,D/PostponalbeReceiver( 5112): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/GBoardtInterface( 2085): onReloaded()
,I/GBoardWebViewClient( 2085): onPageFinished url:file:///android_asset/www/main.html
I/ActivityManager( 1034): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6173 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/BoardContentProvider( 2724): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2724): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1920): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2724): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2724): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1920): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2724): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2724): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2724): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2724): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2724): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2085): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2085): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2085): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2085): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,D/GBoardUriUtils( 2085): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1447937693376&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2085): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1447937693376&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
E/SQLiteDatabase( 6173): Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
E/SQLiteDatabase( 6173): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6173): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6173): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6173): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6173): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6173): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6173): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6173): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6173): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6173): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6173): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6173): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6173): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6173): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6173): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/SQLiteDatabase( 6173): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 6173): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 6173): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 6173): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 6173): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 6173): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 6173): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 6173): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6173): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6173): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 6173): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6173): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6173): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 6173): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/LifetrackerProvider2( 6173): Unable to open database for writing.
E/LifetrackerProvider2( 6173): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LifetrackerProvider2( 6173): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LifetrackerProvider2( 6173): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LifetrackerProvider2(, 6173): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LifetrackerProvider2( 6173): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LifetrackerProvider2( 6173): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LifetrackerProvider2( 6173): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LifetrackerProvider2( 6173): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/LifetrackerProvider2( 6173): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/LifetrackerProvider2( 6173): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LifetrackerProvider2( 6173): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/LifetrackerProvider2( 6173): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/LifetrackerProvider2( 6173): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/LifetrackerProvider2( 6173): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/LifetrackerProvider2( 6173): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/LifetrackerProvider2( 6173): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/LifetrackerProvider2( 6173): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/LifetrackerProvider2( 6173): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/LifetrackerProvider2( 6173): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/LifetrackerProvider2( 6173): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/LifetrackerProvider2( 6173): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/LifetrackerProvider2( 6173): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/LifetrackerProvider2( 6173): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LifetrackerProvider2( 6173): 	at android.os.Looper.loop(Looper.java:135)
E/LifetrackerProvider2( 6173): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/LifetrackerProvider2( 6173): 	at java.lang.reflect.Method.invoke(Native Method)
E/LifetrackerProvider2( 6173): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/LifetrackerProvider2( 6173): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/LifetrackerProvider2( 6173): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/ActivityThread( 6173): Failed to find provider info for com.lge.lgaccount.provider

```
