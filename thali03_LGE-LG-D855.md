#### Test 50388019385b4d9_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 77872965439; DSPS: 2692891; Offset : -4323101111
,D/AndroidRuntime( 5967): 
D/AndroidRuntime( 5967): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5967): CheckJNI is OFF
D/AndroidRuntime( 5967): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1030): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1960): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1030): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{85c4867 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{85c4867 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1030): AppWindowTokenEx init.. 
E/GBMv2   (  347): DFP En is all cleared set to be enabled
I/ActivityManager( 1030): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5982 uid=10319 gids={50319, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5967): Shutting down VM
V/ActivityManager( 1030): Display changed displayId=0
D/DSDPConnection( 1864): Display #0 changed.
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{94cd2d1 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{3c97a136 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 5982): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/WebViewFactory( 5982): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 5982): Loading: webviewchromium
I/LibraryLoader( 5982): Time to load native libraries: 3 ms (timestamps 8689-8692)
I/LibraryLoader( 5982): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5982): Binding Chromium to main looper Looper (main, tid 1) {25fa9af2}
,I/LibraryLoader( 5982): Expected native library version number "",actual native library version number ""
I/chromium( 5982): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5982): Initializing chromium process, renderers=0
,W/art     ( 5982): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5982): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  327): registerClient() client 0xb14275c0, uid 10319
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e0089b9:true
D/BluetoothAdapter( 5982): 269870403: getState() :  mService = null. Returning STATE_OFF
W/chromium( 5982): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5982): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5982): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 5982): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5982): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5982): Build Date: 12/12/14 금
I/Adreno-EGL( 5982): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5982): Remote Branch: 
I/Adreno-EGL( 5982): Local Patches: 
I/Adreno-EGL( 5982): Reconstruct Branch: 
,W/chromium( 5982): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 5982): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 5982): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5982): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5982): CordovaWebView is running on device made by: LGE
,D/UEI.SmartControl( 5915): Internal timer expired: 1
D/UEI.SmartControl( 5915): unbind internal service
D/UEI.SmartControl( 5915): Service.onUnbind: IControl
D/UEI.SmartControl( 5915): Service.onDestroy
D/UEI.SmartControl( 5915): Lock is in USE false
D/UEI.SmartControl( 5915): unbind internal service
W/System.err( 5915): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3b800fec
W/System.err( 5915): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 5915): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 5915): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 5915): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 5915): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 5915): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 5915): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 5915): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 5915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5915): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5915): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5915): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5915): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5915): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5915): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5915): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3b800fec
W/art     ( 5982): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5982): Attempt to remove local handle scope entry from IRT, ignoring
D/serial_port( 5915): close(fd = 25)
I/UEI.SmartControl( 5915): Serial port is closed.
,I/UEI.SmartControl( 5915): Serial port is closed.
D/UEI.SmartControl( 5915): Blaster closed
D/UEI.SmartControl( 5915): Shut down QS...
D/UEI.SmartControl( 5915): Stopping QS lib
D/UEI.SmartControl( 5915): QS lib stop result = true
D/UEI.SmartControl( 5915): Stopped QS lib
D/UEI.SmartControl( 5915): Stopped file observer...
D/UEI.SmartControl( 5915): QS shutdown complete
,D/OpenGLRenderer( 5982): Render dirty regions requested: true
I/OpenGLRenderer( 5982): Initialized EGL, version 1.4
D/OpenGLRenderer( 5982): Enabling debug mode 0
,D/Atlas   ( 5982): Validating map...
D/SplitWindow( 1030): check instance of lgWin Window{2918ee6b u0 com.example.hello/com.example.hello.MainActivity}
,D/LgDataFeature( 5982): LgDataFeature() Constructor: none
D/LgDataFeature( 5982): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1461): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
,W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2183e02c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/Timeline( 5982): Timeline: Activity_idle id: android.os.BinderProxy@186aa533 time:79186
I/ActivityManager( 1030): Displayed com.example.hello/.MainActivity: +609ms (total +719ms)
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{14046614 u0 com.example.hello/.MainActivity t4} time:79189
,I/chromium( 5982): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 5982): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 5982): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5982): 
,D/JsMessageQueue( 5982): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 5982): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5982): 
,W/ProcessCpuTracker( 1030): Skipping unknown process pid 6003
W/ProcessCpuTracker( 1030): Skipping unknown process pid 6006
,D/jxcore_app_log( 5982): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435358464
D/JX-Cordova( 5982): jxcore cordova android initializing
W/jxcore-log( 5982): Initializing JXcore engine
W/jxcore-log( 5982): JXcore engine is ready
,W/jxcore-log( 5982): Starting JXcore engine
I/ActivityManager( 1030): Killing 5497:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/m.example.hello( 5982): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9824]" dev="sockfs" ino=9824 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 5982): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 5982): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7596]" dev="sockfs" ino=7596 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 5982): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/m.example.hello( 5982): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[27993]" dev="sockfs" ino=27993 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/libprocessgroup( 1030): failed to open /acct/uid_10008/pid_5497/cgroup.procs: No such file or directory
,W/jxcore-log( 5982): Platform android
W/jxcore-log( 5982): 
W/jxcore-log( 5982): Process ARCH arm
W/jxcore-log( 5982): 
,E/GBMv2   (  347): DFP En is all cleared set to be enabled
E/GBMv2   (  347): Set value is all cleared set the max
I/GBMv2   (  347): DFP Enabled. Ignore VFP set
,I/jxcore-log( 5982): JXcore Cordova bridge is ready!
I/jxcore-log( 5982): 
,W/jxcore-log( 5982): JXcore engine is started
E/jxcore-log( 5982): >> LGE-LG-D855
E/jxcore-log( 5982): 
,I/jxcore-log( 5982): Total memory 2995761152
I/jxcore-log( 5982): 
I/jxcore-log( 5982): Free memory 653963264
I/jxcore-log( 5982): 
I/jxcore-log( 5982): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5982): 
I/jxcore-log( 5982): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5982): 
I/jxcore-log( 5982): userPath [ 'www' ]
I/jxcore-log( 5982): 
I/jxcore-log( 5982): Size 1440 2392
I/jxcore-log( 5982): 
,I/jxcore-log( 5982): Screen Brightness 50
I/jxcore-log( 5982): 
E/jxcore-log( 5982): Dummy Error Log.
E/jxcore-log( 5982): 
I/jxcore-log( 5982): getBuffer is called!!!!
I/jxcore-log( 5982): 
,D/InitAlarmsService( 4883): Clearing and rescheduling alarms.
,I/ActivityManager( 1030): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6076 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 6076): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6076): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@302cfe66
,D/CalendarProvider2( 6076): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6076): Created com.android.providers.calendar.CalendarAlarmManager@1015e543(com.android.providers.calendar.CalendarProvider2@302cfe66)
D/CalendarProvider2( 6076): Scheduling check of next Alarm
D/CalendarProvider2( 6076): SCHEDULE_ALARM_REMOVE
,I/ActivityManager( 1030): Killing 4883:com.android.calendar/u0a13 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10013/pid_4883/cgroup.procs: No such file or directory
,I/CalendarProvider2( 6076): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6076): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager( 1030): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6103 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1030): Killing 5562:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_5562/cgroup.procs: No such file or directory
W/ResourcesManager( 6103): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CalendarApplication( 6103): CalendarApplication.onCreate()
D/PreferenceKeysParser( 6103): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6103): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2fe5ca54, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3974edfd, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@25fa9af2, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1015e543, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@19ff37c0, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@33276cf9, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@c93743e, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2e27929f, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3b800fec, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@16e8dfb5, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@304e964a, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@a7cb9bb, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@19543ed8, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2714c231, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@19e7cd16, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1d333697, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@193a7084, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1642506d, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@100ba4a2, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@186aa533, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1c3010f0, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2f408669, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@25a368ee, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@26a0618f, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@139d4c1c, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@d22025, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@20e125fa, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@32cb87ab, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3d410e08, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@92999a1, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@70ba7c6, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1638f387, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@31dd02b4, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1d252edd, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@190a7a52, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@8274123, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@32a19620, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@74adbd9, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@cb1e99e, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2b22cc7f, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@2159f44c, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1a845c9
D/GeneralPreferenceUtils( 6103): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6103): [init]
I/Config  ( 6103): LGCalendar ver.4.40.16
I/Config  ( 6103): start check model
I/Config  ( 6103): start check native_ca
I/Config  ( 6103): Config Operator=OPEN, Country=EU
D/Config  ( 6103): [setDefaultValuesToPref]
D/Config  ( 6103): [parseProfiles]
D/ProfilesParser( 6103): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6103): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6103): [updateProfiletoCountryInfo]
D/GeneralPreference( 6103): [checkAndMigrateOldPreference]
D/AlertReceiver( 6103): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6103): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6103): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6103): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6103): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6103): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6103): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6103): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6103): onHandleIntent
D/HolidayDataLoader( 6103): readJsonAsset : holiday.json
D/AlertService( 6103): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6103): [updateWidgets] 
D/MonthWidgetProvider( 6103): [onReceive]
D/CalendarWidgetProvider( 6103): [onReceive]
D/CalendarWidgetProvider( 6103): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6103): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6103): [onReceive]
D/CalendarWidgetProvider( 6103): [onReceive]
D/CalendarWidgetProvider( 6103): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6103): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6103): onHandleIntent:holiday data empty
,I/ActivityManager( 1030): Waited long enough for: ServiceRecord{13661ca7 u0 com.google.android.music/.wear.WearMetadataSyncService}
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1030): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService( 1030): Message: 2
D/WifiService( 1030): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1030): setWifiEnabled: false pid=5982, uid=10319, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1030): setWifiEnabled: false pid=5982, uid=10319
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 5982): ****TEST TOOK:  5058  ms ****
I/jxcore-log( 5982): 
I/jxcore-log( 5982): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5982): 
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3af6485b type 2 when 87287 com.android.providers.calendar} when 87287
,D/CalendarProviderBroadcastReceiver( 6076): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 6076): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6076): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6076): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6076): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6076): (284) automatic index on view_events(_id)
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{8b72436 type 0 when 1450189353672 com.android.vending} when 1450189353672
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CalendarProvider2( 6076): [IntentService] Release Lock
,D/CalendarProvider2( 6076): CalendarProviderIntentService.onDestroy()
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,D/AndroidRuntime( 6157): 
D/AndroidRuntime( 6157): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6157): CheckJNI is OFF
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5740): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5740): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5740): [1] 5.onFinished: Scheduling replication attempt 1.
D/AndroidRuntime( 6157): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1030): Force stopping com.example.hello appid=10319 user=-1: uninstall pkg
,I/ActivityManager( 1030): Killing 5982:com.example.hello/u0a319 (adj 0): stop com.example.hello
I/WindowState( 1030): WIN DEATH: Window{2918ee6b u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1030): Client connection lost with reason: 4
D/InputDispatcher( 1030): Window went away: Window{2918ee6b u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings( 1030): Skipping PackageSetting{19db8311 com.test.thalitest/10311} due to missing metadata
,I/ActivityManager( 1030):   Force finishing activity ActivityRecord{14046614 u0 com.example.hello/.MainActivity t4}
,E/GBMv2   (  347): DFP En is all cleared set to be enabled
,W/ActivityManager( 1030): Spurious death for ProcessRecord{385a5028 5982:com.example.hello/u0a319}, curProc for 5982: null
I/ActivityManager( 1030): Force stopping com.example.hello appid=10319 user=0: pkg removed
I/ActivityManager( 1030):   Force finishing activity ActivityRecord{14046614 u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager( 1030): Duplicate finish request for ActivityRecord{14046614 u0 com.example.hello/.MainActivity t4 f}
,I/[LGHome]EVENT( 2082): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2082): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{25724837 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{1533b1a4 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Service_RemotePackageHandler( 2026): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
,D/LIA_MrGDBLogger_PackageInfoDetector( 2688): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
D/ActionManagerService( 1917): notifyUserLog: 1000003
I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2082): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/LIA_Informant_ActionManagerMessageHandler( 2688): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]EVENT( 2082): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2082): [Launcher.java:1114:onPause()]onPause
,W/GeofencerStateMachine( 1829): Ignoring removeGeofence because network location is disabled.
I/[SystemUI]QSlideListController( 1461): onReceive = android.intent.action.PACKAGE_REMOVED
D/PostponalbeReceiver( 5206): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4226): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
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
D/ActionManagerService( 1917): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 2688): handleMessage: what(1000) actionID(0x1000004)
,V/BoardContentProvider( 2688): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2082): , create_time: 1430558575574
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
D/KeyguardModel( 1461): createShortcutInfo...
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2082): , create_time: 1430558575600
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1449757673225
I/GBoardWebViewUtils( 2082): , create_time: 1449757673771
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1449757673225&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
D/WallpaperManager( 2082): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1461): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2183e02c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
D/AppUp4:PreloadHelper( 5518): added Exclude : com.example.hello
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/SplitUIManager( 1882): split_name #11 / not available #0
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
D/SplitUIService( 1882): removed split : 
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
D/KeyguardModel( 1461): handleShortcutListChanged...
,D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1461): createShortcutInfo...
D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/SplitUIManager( 1882): split_name #11 / not available #0
I/SplitUIService( 1882): split app #11
D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
D/VoicemailCleanupService( 2226): Cleaning up data for package: com.example.hello
I/art     ( 4271): Explicit concurrent mark sweep GC freed 15868(922KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 933us total 123.606ms
,I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6202 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 2082): [Launcher.java:5349:onStop()]onStop
I/art     ( 1030): Explicit concurrent mark sweep GC freed 16823(1153KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 11.940ms total 197.265ms
I/art     ( 1030): WaitForGcToComplete blocked for 183.705ms for cause Explicit
D/KeyguardModel( 1461): handleShortcutListChanged...
,D/administrator( 1030): Handling package changes for user 0
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/ResourcesManager( 6202): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6202): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6202): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6202): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/NotificationService( 1030): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1030): Receieved: android.intent.action.PACKAGE_REMOVED
,I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/TaskPersister( 1030): removeObsoleteFile: deleting file=4_task.xml
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{1a60b937 u0 com.lge.launcher2/.Launcher t3} time:88528
D/PhoneStatusBar( 1461): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/LGEmail ( 6202): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/LGEmail ( 6202): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,I/[Concierge]WidgetView( 2082): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2603): onStartCommand(). Type : 8
D/[Concierge]Service( 2603): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,D/[Concierge]Service( 2603): Update widget ID : 11
D/[Concierge]WidgetView( 2082): change position of spinner
I/art     ( 1030): Explicit concurrent mark sweep GC freed 7126(394KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.706ms total 204.001ms
,D/[Concierge]Service( 2603): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2082): initWebView(). Time : 1450189357755
I/[Concierge]WebView( 2082): Return exist ConciergeWebView. Reuse : 882799340
D/[Concierge]WidgetView( 2082): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2082): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2f67e0e5
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourceType( 6202): No package identifier when getting value for resource number 0x00000000
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2082): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2082): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2082): Widget kill message received. Destory myself. My : 1450189297274, New one : 1450189357755
D/[Concierge]WidgetView( 2082): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2082): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/LgDataFeature( 6202): LgDataFeature() Constructor: none
D/LgDataFeature( 6202): LgDataFeature() Constructor Done, null
,D/AndroidRuntime( 6157): Shutting down VM
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2082): Timeline: Activity_idle id: android.os.BinderProxy@2074b22d time:88691
,W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/PackageChangeReceiver( 6202): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager( 1030): Killing 5607:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,I/chromium( 2082): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,D/LIA_Service_NativeEventReceiver( 2026): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
I/LIA_Service_PlatformUtil( 2026): startLIAService() : Trying to start LIA service ...
,W/libprocessgroup( 1030): failed to open /acct/uid_10061/pid_5607/cgroup.procs: No such file or directory
D/LIA_Service_LIAService( 2026): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
I/GBoardtInterface( 2082): onReloaded()
,D/PostponalbeReceiver( 5206): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/GBoardWebViewClient( 2082): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2688): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/AlertService( 6103): Beginning updateAlertNotification
,I/ActivityManager( 1030): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6229 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/BoardContentProvider( 2688): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/AlertService( 6103): No fired or scheduled alerts
,D/ActionManagerService( 1917): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2688): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2688): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1917): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2688): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2688): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2688): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2688): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2688): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/GBoardUriUtils( 2082): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2082): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2082): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2082): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/AlertService( 6103): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/GBoardUriUtils( 2082): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1449757673225&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2082): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1449757673225&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
E/SQLiteLog( 6076): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DatabaseUtils( 6076): Writing exception to parcel
E/DatabaseUtils( 6076): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 6076): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 6076): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
E/DatabaseUtils( 6076): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 6076): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 6076): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DatabaseUtils( 6076): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DatabaseUtils( 6076): 	at com.android.providers.calendar.CalendarProvider2.acquireInstanceRange(CalendarProvider2.java:1418)
E/DatabaseUtils( 6076): 	at com.android.providers.calendar.CalendarProvider2.handleInstanceQuery(CalendarProvider2.java:1146)
E/DatabaseUtils( 6076): 	at com.android.providers.calendar.CalendarProvider2.queryInternal(CalendarProvider2.java:966)
E/DatabaseUtils( 6076): 	at com.android.providers.calendar.CalendarProvider2.query(CalendarProvider2.java:865)
E/DatabaseUtils( 6076): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 6076): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 6076): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 6076): 	at android.os.Binder.execTransact(Binder.java:446)
--------- beginning of crash
E/AndroidRuntime( 6103): FATAL EXCEPTION: AlertService
E/AndroidRuntime( 6103): Process: com.android.calendar, PID: 6103
E/AndroidRuntime( 6103): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6103): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 6103): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 6103): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
E/AndroidRuntime( 6103): 	at android.content.ContentResolver.query(ContentResolver.java:481)
E/AndroidRuntime( 6103): 	at android.content.ContentResolver.query(ContentResolver.java:425)
E/AndroidRuntime( 6103): 	at com.android.calendar.alerts.AlarmScheduler.queryUpcomingEvents(AlarmScheduler.java:168)
E/AndroidRuntime( 6103): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:115)
E/AndroidRuntime( 6103): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:106)
E/AndroidRuntime( 6103): 	at com.android.calendar.alerts.AlertService.processMessage(AlertService.java:292)
E/AndroidRuntime( 6103): 	at com.android.calendar.alerts.AlertService$ServiceHandler.handleMessage(AlertService.java:1202)
E/AndroidRuntime( 6103): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6103): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6103): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 6103): Sending signal. PID: 6103 SIG: 9

```
