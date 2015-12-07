#### Test 50242285e707819_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
,D/UEI.SmartControl( 5874): Internal timer expired: 1
D/UEI.SmartControl( 5874): unbind internal service
D/UEI.SmartControl( 5874): Service.onUnbind: IControl
D/UEI.SmartControl( 5874): Service.onDestroy
D/UEI.SmartControl( 5874): Lock is in USE false
D/UEI.SmartControl( 5874): unbind internal service
W/System.err( 5874): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1d851109
W/System.err( 5874): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 5874): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 5874): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 5874): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 5874): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 5874): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 5874): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 5874): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 5874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5874): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5874): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5874): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5874): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5874): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5874): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5874): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1d851109
D/serial_port( 5874): close(fd = 25)
I/UEI.SmartControl( 5874): Serial port is closed.
I/UEI.SmartControl( 5874): Serial port is closed.
D/UEI.SmartControl( 5874): Blaster closed
D/UEI.SmartControl( 5874): Shut down QS...
D/UEI.SmartControl( 5874): Stopping QS lib
D/UEI.SmartControl( 5874): QS lib stop result = true
D/UEI.SmartControl( 5874): Stopped QS lib
D/UEI.SmartControl( 5874): Stopped file observer...
D/UEI.SmartControl( 5874): QS shutdown complete
D/sensors_hal_Time( 1027): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1027): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1027): tsOffsetIs: Apps: 77649486692; DSPS: 2685133; Offset : -4308386701
D/AndroidRuntime( 5919): 
D/AndroidRuntime( 5919): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5919): CheckJNI is OFF
D/AndroidRuntime( 5919): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1027): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1954): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1027): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1027): setTaskToReturnTo : TaskRecord{78d4c59 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1027): setTaskToReturnTo : TaskRecord{78d4c59 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1027): AppWindowTokenEx init.. 
E/GBMv2   (  342): DFP En is all cleared set to be enabled
I/ActivityManager( 1027): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5941 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5919): Shutting down VM
V/ActivityManager( 1027): Display changed displayId=0
D/DSDPConnection( 1865): Display #0 changed.
D/SplitWindowPolicy( 1954): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1954): topRunningActivity=ActivityInfo{286c783a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1954): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1954): topRunningActivity=ActivityInfo{39ad0ceb co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
I/ActivityManager( 1027): Killing 5434:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1027): failed to open /acct/uid_10008/pid_5434/cgroup.procs: No such file or directory
D/ContextHelper( 5941): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/WebViewFactory( 5941): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 5941): Loading: webviewchromium
I/LibraryLoader( 5941): Time to load native libraries: 4 ms (timestamps 8126-8130)
I/LibraryLoader( 5941): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5941): Binding Chromium to main looper Looper (main, tid 1) {376fe37}
I/LibraryLoader( 5941): Expected native library version number "",actual native library version number ""
,I/chromium( 5941): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5941): Initializing chromium process, renderers=0
W/art     ( 5941): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5941): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 5941): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5941): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5941): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  324): registerClient() client 0xb1426f40, uid 10318
,D/BluetoothManagerService( 1027): Message: 20
D/BluetoothManagerService( 1027): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16fc9e1b:true
D/BluetoothAdapter( 5941): 279523236: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 5941): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5941): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5941): Build Date: 12/12/14 금
I/Adreno-EGL( 5941): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5941): Remote Branch: 
I/Adreno-EGL( 5941): Local Patches: 
I/Adreno-EGL( 5941): Reconstruct Branch: 
W/chromium( 5941): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 5941): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 5941): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5941): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5941): CordovaWebView is running on device made by: LGE
,W/art     ( 5941): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5941): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5941): Render dirty regions requested: true
I/OpenGLRenderer( 5941): Initialized EGL, version 1.4
D/OpenGLRenderer( 5941): Enabling debug mode 0
,D/Atlas   ( 5941): Validating map...
,D/SplitWindow( 1027): check instance of lgWin Window{22ca083d u0 com.example.hello/com.example.hello.MainActivity}
,I/SystemUI[Framework]( 1027): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1027): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1027): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1027): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1027): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@4aca44d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1027): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1466): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 5941): LgDataFeature() Constructor: none
D/LgDataFeature( 5941): LgDataFeature() Constructor Done, null
,I/Timeline( 5941): Timeline: Activity_idle id: android.os.BinderProxy@3c89c9d4 time:78516
,I/ActivityManager( 1027): Displayed com.example.hello/.MainActivity: +572ms (total +665ms)
I/Timeline( 1027): Timeline: Activity_windows_visible id: ActivityRecord{2a42d01e u0 com.example.hello/.MainActivity t4} time:78541
I/chromium( 5941): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 5941): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 5941): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5941): 
,D/JsMessageQueue( 5941): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 5941): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5941): 
,D/jxcore_app_log( 5941): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435327232
D/JX-Cordova( 5941): jxcore cordova android initializing
,W/jxcore-log( 5941): Initializing JXcore engine
,W/jxcore-log( 5941): JXcore engine is ready
,W/jxcore-log( 5941): Starting JXcore engine
,W/m.example.hello( 5941): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10281]" dev="sockfs" ino=10281 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 5941): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 5941): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7581]" dev="sockfs" ino=7581 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 5941): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,W/m.example.hello( 5941): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29885]" dev="sockfs" ino=29885 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 5941): Platform android
W/jxcore-log( 5941): 
,W/jxcore-log( 5941): Process ARCH arm
W/jxcore-log( 5941): 
,I/jxcore-log( 5941): JXcore Cordova bridge is ready!
I/jxcore-log( 5941): 
,W/jxcore-log( 5941): JXcore engine is started
,E/jxcore-log( 5941): >> LGE-LG-D855
E/jxcore-log( 5941): 
I/jxcore-log( 5941): Total memory 2995761152
I/jxcore-log( 5941): 
I/jxcore-log( 5941): Free memory 648044544
I/jxcore-log( 5941): 
I/jxcore-log( 5941): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5941): 
I/jxcore-log( 5941): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5941): 
,I/jxcore-log( 5941): userPath [ 'www' ]
I/jxcore-log( 5941): 
I/jxcore-log( 5941): Size 1440 2392
I/jxcore-log( 5941): 
I/jxcore-log( 5941): Screen Brightness 50
I/jxcore-log( 5941): 
E/jxcore-log( 5941): Dummy Error Log.
E/jxcore-log( 5941): 
,E/GBMv2   (  342): DFP En is all cleared set to be enabled
E/GBMv2   (  342): Set value is all cleared set the max
I/GBMv2   (  342): DFP Enabled. Ignore VFP set
,I/jxcore-log( 5941): getBuffer is called!!!!
I/jxcore-log( 5941): 
,D/InitAlarmsService( 4859): Clearing and rescheduling alarms.
,I/ActivityManager( 1027): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6004 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 6004): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6004): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2535475b
,D/CalendarProvider2( 6004): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6004): Created com.android.providers.calendar.CalendarAlarmManager@10a92fa4(com.android.providers.calendar.CalendarProvider2@2535475b)
D/CalendarProvider2( 6004): Scheduling check of next Alarm
D/CalendarProvider2( 6004): SCHEDULE_ALARM_REMOVE
,I/ActivityManager( 1027): Killing 4859:com.android.calendar/u0a13 (adj 15): empty #17
W/libprocessgroup( 1027): failed to open /acct/uid_10013/pid_4859/cgroup.procs: No such file or directory
,I/CalendarProvider2( 6004): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6004): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 1027): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6038 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1027): Killing 5508:com.lge.email/u0a23 (adj 15): empty #17
,I/ActivityManager( 1027): Waited long enough for: ServiceRecord{ec9955e u0 com.google.android.music/.wear.WearMetadataSyncService}
,W/libprocessgroup( 1027): failed to open /acct/uid_10023/pid_5508/cgroup.procs: No such file or directory
W/ResourcesManager( 6038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6038): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6038): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6038): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@13918d1, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2d856f36, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@376fe37, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@10a92fa4, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2165710d, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1db148c2, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@30b346d3, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@361ba210, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1d851109, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@12cf2f0e, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@15617d2f, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1000cf3c, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@13e4b4c5, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3cd32e1a, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@12bd4b, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@30a9a328, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@e0d841, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@24e611e6, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@d4de327, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3c89c9d4, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3021b77d, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2bf16672, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@312b8ac3, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@9a3af40, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@5974e79, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@25eb77be, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3eb2101f, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@9b47f6c, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1a355935, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1de351ca, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@8f18f3b, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2b202658, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@286f53b1, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@eccc096, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@39dfe417, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1c9d5004, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@47479ed, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1d0c5022, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3af4aab3, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1fa16870, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1c2bc7e9, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1cc34c6e, l
D/GeneralP,referenceUtils( 6038): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6038): [init]
,I/Config  ( 6038): LGCalendar ver.4.40.16
I/Config  ( 6038): start check model
I/Config  ( 6038): start check native_ca
I/Config  ( 6038): Config Operator=OPEN, Country=EU
D/Config  ( 6038): [setDefaultValuesToPref]
D/Config  ( 6038): [parseProfiles]
D/ProfilesParser( 6038): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6038): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6038): [updateProfiletoCountryInfo]
D/GeneralPreference( 6038): [checkAndMigrateOldPreference]
D/AlertReceiver( 6038): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6038): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6038): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6038): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6038): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6038): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6038): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6038): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6038): onHandleIntent
D/HolidayDataLoader( 6038): readJsonAsset : holiday.json
D/AlertService( 6038): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6038): [updateWidgets] 
D/MonthWidgetProvider( 6038): [onReceive]
D/CalendarWidgetProvider( 6038): [onReceive]
D/CalendarWidgetProvider( 6038): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6038): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6038): [onReceive]
D/CalendarWidgetProvider( 6038): [onReceive]
D/CalendarWidgetProvider( 6038): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6038): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6038): onHandleIntent:holiday data empty
,D/BluetoothManagerService( 1027): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1027): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService( 1027): Message: 2
D/WifiService( 1027): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1027): setWifiEnabled: false pid=5941, uid=10318, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1027): setWifiEnabled: false pid=5941, uid=10318
E/WifiService( 1027): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 5941): ****TEST TOOK:  5068  ms ****
I/jxcore-log( 5941): 
I/jxcore-log( 5941): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5941): 
V/AlarmManager( 1027): ELAPSED_WAKEUP set : Alarm{31327aad type 2 when 86871 com.android.providers.calendar} when 86871
,D/CalendarProviderBroadcastReceiver( 6004): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 6004): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6004): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6004): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6004): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6004): (284) automatic index on view_events(_id)
V/AlarmManager( 1027): RTC_WAKEUP set : Alarm{1ad67973 type 0 when 1449498975709 com.lge.ia.task.mrgdblogger} when 1449498975709
,D/LIA_MrGDBLogger_MrGIntentReceiverDBCleaning( 2699): [dreamwood]onReceive
,D/LIA_MrGDBLogger_MrGDBCleaner( 2699): [dreamwood]onReceive
V/AlarmManager( 1027): RTC_WAKEUP set : Alarm{1ba914a9 type 0 when 1449499005574 com.android.vending} when 1449499005574
,V/AlarmManager( 1027): ELAPSED_WAKEUP set : Alarm{2eff7a2e type 2 when 86619 com.google.android.gms} when 86619
,D/LIA_MrGDBLogger_MrGDBManager( 2699): [dreamwood]dbFileSize : 77824
,D/libc-netbsd(  319): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1027): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CalendarProvider2( 6004): [IntentService] Release Lock
,D/CalendarProvider2( 6004): CalendarProviderIntentService.onDestroy()
D/LIA_MrGDBLogger_DBCleanerUtil( 2699): [dreamwood]cleanOldRecord : APP_USAGE
D/LIA_MrGDBLogger_DBCleanerUtil( 2699): [dreamwood]LimitedDate : 2015-11-07 15:36:49, count : 0
D/LIA_MrGDBLogger_DBCleanerUtil( 2699): [dreamwood]cleanOldRecord : CONCIERGE_BOARD
D/LIA_MrGDBLogger_DBCleanerUtil( 2699): [dreamwood]LimitedDate : 2015-11-07 15:36:49, count : 0
D/LIA_MrGDBLogger_DBCleanerUtil( 2699): [dreamwood]cleanOldRecord : INFORMANT_FEATURE_STATUS_INFO
,D/LIA_MrGDBLogger_DBCleanerUtil( 2699): [dreamwood]LimitedDate : 2015-11-07 15:36:49, count : 0
D/libc-netbsd(  319): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1027): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LIA_MrGDBLogger_MrGDBManager( 2699): [dreamwood]dbFileSize : 77824
V/SIM_STK ( 1027): Menu title from STK is T-Mobile
,D/AndroidRuntime( 6074): 
D/AndroidRuntime( 6074): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6074): CheckJNI is OFF
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5691): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5691): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5691): [1] 5.onFinished: Scheduling replication attempt 1.
,D/AndroidRuntime( 6074): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1027): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
,I/ActivityManager( 1027): Killing 5941:com.example.hello/u0a318 (adj 0): stop com.example.hello
I/WindowState( 1027): WIN DEATH: Window{22ca083d u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1027): Client connection lost with reason: 4
D/InputDispatcher( 1027): Window went away: Window{22ca083d u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings( 1027): Skipping PackageSetting{2e46ff7a com.test.thalitest/10311} due to missing metadata
,E/libprocessgroup( 1027): failed to kill 1 processes for processgroup 5941
,I/ActivityManager( 1027):   Force finishing activity ActivityRecord{2a42d01e u0 com.example.hello/.MainActivity t4}
,E/GBMv2   (  342): DFP En is all cleared set to be enabled
W/ActivityManager( 1027): Spurious death for ProcessRecord{64cc560 5941:com.example.hello/u0a318}, curProc for 5941: null
I/ActivityManager( 1027): Force stopping com.example.hello appid=10318 user=0: pkg removed
,I/ActivityManager( 1027):   Force finishing activity ActivityRecord{2a42d01e u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager( 1027): Duplicate finish request for ActivityRecord{2a42d01e u0 com.example.hello/.MainActivity t4 f}
,D/SplitWindowPolicy( 1954): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1954): topRunningActivity=ActivityInfo{31604a48 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2082): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1954): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2082): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1954): topRunningActivity=ActivityInfo{1851c0e1 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2082): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/GeofencerStateMachine( 1830): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 2027): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
I/InputReader( 1027): Reconfiguring input devices.  changes=0x00000010
,D/LIA_MrGDBLogger_PackageInfoDetector( 2699): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
D/ActionManagerService( 1918): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2699): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2082): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 2082): [Launcher.java:1056:onResume()]onResume end
D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
I/[LGHome]EVENT( 2082): [Launcher.java:1114:onPause()]onPause
I/[SystemUI]QSlideListController( 1466): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 2699): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1918): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2699): handleMessage: what(1000) actionID(0x1000004)
,I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
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
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1449156806130
I/GBoardWebViewUtils( 2082): , create_time: 1449156807049
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,I/SystemUI[Framework]( 1027): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1027): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1027): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1027): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1027): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@4aca44d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1027): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WallpaperManager( 2082): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,D/SplitUIManager( 1882): split_name #11 / not available #0
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/KeyguardModel( 1466): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1466): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1466): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/SplitUIService( 1882): removed split : 
,D/KeyguardModel( 1466): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1466): createShortcutInfo...
W/System.err( 4201): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 4201): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4201): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4201): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4201): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4201): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4201): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4201): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4201): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4201): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4201): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/KeyguardModel( 1466): handleShortcutListChanged...
V/SIM_STK ( 1027): Menu title from STK is T-Mobile
D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
I/art     ( 4249): Explicit concurrent mark sweep GC freed 15755(916KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 595us total 154.975ms
,D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1466): createShortcutInfo...
,W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1466): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1466): createShortcutInfo...
D/SplitUIManager( 1882): split_name #11 / not available #0
I/SplitUIService( 1882): split app #11
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1466): createShortcutInfo...
D/KeyguardModel( 1466): handleShortcutListChanged...
,I/[LGHome]EVENT( 2082): [Launcher.java:5349:onStop()]onStop
,D/AppUp4:PreloadHelper( 5464): added Exclude : com.example.hello
D/VoicemailCleanupService( 2187): Cleaning up data for package: com.example.hello
I/art     ( 1027): Explicit concurrent mark sweep GC freed 17482(1192KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.957ms total 203.978ms
,I/art     ( 1027): WaitForGcToComplete blocked for 201.972ms for cause Explicit
I/ActivityManager( 1027): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6124 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/administrator( 1027): Handling package changes for user 0
,V/SIM_STK ( 1027): Menu title from STK is T-Mobile
,I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/ResourcesManager( 6124): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6124): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6124): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6124): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/Timeline( 1027): Timeline: Activity_windows_visible id: ActivityRecord{e715748 u0 com.lge.launcher2/.Launcher t3} time:88091
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[Concierge]WidgetView( 2082): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2610): onStartCommand(). Type : 8
D/[Concierge]Service( 2610): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2610): Update widget ID : 11
D/[Concierge]WidgetView( 2082): change position of spinner
I/NotificationService( 1027): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1027): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1027): Receieved: android.intent.action.PACKAGE_REMOVED
,D/PhoneStatusBar( 1466): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1027): removeObsoleteFile: deleting file=4_task.xml
I/[Concierge]WidgetView( 2082): initWebView(). Time : 1449499010776
D/[Concierge]Service( 2610): onStartCommand(). Type : 0
I/[Concierge]WebView( 2082): Return exist ConciergeWebView. Reuse : 863697995
D/[Concierge]WidgetView( 2082): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2082): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2886f03d
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2082): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2082): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/LGEmail ( 6124): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/[Concierge]WidgetView( 2082): Widget kill message received. Destory myself. My : 1449498950772, New one : 1449499010776
D/[Concierge]WidgetView( 2082): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2082): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/LGEmail ( 6124): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1027): Explicit concurrent mark sweep GC freed 7315(390KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.776ms total 197.594ms
,W/ResourceType( 6124): No package identifier when getting value for resource number 0x00000000
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/AndroidRuntime( 6074): Shutting down VM
,D/LgDataFeature( 6124): LgDataFeature() Constructor: none
D/LgDataFeature( 6124): LgDataFeature() Constructor Done, null
I/Timeline( 2082): Timeline: Activity_idle id: android.os.BinderProxy@3b99a93d time:88285
W/ResourcesManager( 1027): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1027): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/PackageChangeReceiver( 6124): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager( 1027): Killing 5573:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/AlertService( 6038): Beginning updateAlertNotification
,I/chromium( 2082): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,D/LIA_Service_NativeEventReceiver( 2027): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
I/LIA_Service_PlatformUtil( 2027): startLIAService() : Trying to start LIA service ...
,D/LIA_Service_LIAService( 2027): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
I/GBoardtInterface( 2082): onReloaded()
I/GBoardWebViewClient( 2082): onPageFinished url:file:///android_asset/www/main.html
W/libprocessgroup( 1027): failed to open /acct/uid_10061/pid_5573/cgroup.procs: No such file or directory
V/BoardContentProvider( 2699): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/PostponalbeReceiver( 5174): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,I/ActivityManager( 1027): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6150 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/AlertService( 6038): No fired or scheduled alerts
V/BoardContentProvider( 2699): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/ActionManagerService( 1918): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2699): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2699): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1918): notifyUserLog: 1000001
,V/BoardContentProvider( 2699): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 2699): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2699): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2699): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2699): onSettingEvent() : GBoard On - add scheduler - 0
D/GBoardUriUtils( 2082): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2082): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,D/AlertService( 6038): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/GBoardUriUtils( 2082): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2082): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2082): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2082): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
E/SQLiteLog( 6004): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DatabaseUtils( 6004): Writing exception to parcel
E/DatabaseUtils( 6004): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 6004): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 6004): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
E/DatabaseUtils( 6004): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 6004): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 6004): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DatabaseUtils( 6004): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DatabaseUtils( 6004): 	at com.android.providers.calendar.CalendarProvider2.acquireInstanceRange(CalendarProvider2.java:1418)
E/DatabaseUtils( 6004): 	at com.android.providers.calendar.CalendarProvider2.handleInstanceQuery(CalendarProvider2.java:1146)
E/DatabaseUtils( 6004): 	at com.android.providers.calendar.CalendarProvider2.queryInternal(CalendarProvider2.java:966)
E/DatabaseUtils( 6004): 	at com.android.providers.calendar.CalendarProvider2.query(CalendarProvider2.java:865)
E/DatabaseUtils( 6004): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 6004): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 6004): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 6004): 	at android.os.Binder.execTransact(Binder.java:446)
--------- beginning of crash
E/AndroidRuntime( 6038): FATAL EXCEPTION: AlertService
E/AndroidRuntime( 6038): Process: com.android.calendar, PID: 6038
E/AndroidRuntime( 6038): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6038): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 6038): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 6038): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
E/AndroidRuntime( 6038): 	at android.content.ContentResolver.query(ContentResolver.java:481)
E/AndroidRuntime( 6038): 	at android.content.ContentResolver.query(ContentResolver.java:425)
E/AndroidRuntime( 6038): 	at com.android.calendar.alerts.AlarmScheduler.queryUpcomingEvents(AlarmScheduler.java:168)
E/AndroidRuntime( 6038): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:115)
E/AndroidRuntime( 6038): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:106)
E/AndroidRuntime( 6038): 	at com.android.calendar.alerts.AlertService.processMessage(AlertService.java:292)
E/AndroidRuntime( 6038): 	at com.android.calendar.alerts.AlertService$ServiceHandler.handleMessage(AlertService.java:1202)
E/AndroidRuntime( 6038): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6038): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6038): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 1027): Can't write: system_app_crash
E/DropBoxManagerService( 1027): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1027): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1027): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1027): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1027): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1027): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1027): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1027): Ca,used by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1027): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1027): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1027): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1027): 	... 5 more
I/Process ( 6038): Sending signal. PID: 6038 SIG: 9
I/ActivityManager( 1027): Process com.android.calendar (pid 6038) has died
W/ActivityManager( 1027): Scheduling restart of crashed service com.android.calendar/.alerts.AlertService in 10966ms
,E/SQLiteDatabase( 6150): Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
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
E/SQLiteDatabase( 6150): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
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
E/Lifetrac,kerProvider2( 6150): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
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
W/LG Account v2.2( 6150): No ProfileInfo entries
I/LG Account v2.2( 6150): isEnabled: false
I/Feature ( 6150): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6150): [Lifetracker]Country: EU
I/Feature ( 6150): [Lifetracker]Operator: OPEN
I/Feature ( 6150): [Lifetracker]Ranking support: false
I/Feature ( 6150): [Lifetracker]Comfort support: false
I/Feature ( 6150): [Lifetracker]Accessory: true
I/Feature ( 6150): [Lifetracker]Health device: true
I/Feature ( 6150): [Lifetracker]Extra Pedometer: false
I/Feature ( 6150): [Lifetracker]Blood glucose device: false
I/Feature ( 6150): [Lifetracker]Device Number: 3
D/CoreEventReceiver( 6150): [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,E/GBMv2   (  342): DFP En is all cleared set to be enabled
E/GBMv2   (  342): Set value is all cleared set the max

```
