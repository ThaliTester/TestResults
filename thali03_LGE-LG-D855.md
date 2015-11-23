#### Test 503880196b4ec73_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
I/ActivityManager( 1031): Killing 5563:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10023/pid_5563/cgroup.procs: No such file or directory
--------- beginning of main
D/AndroidRuntime( 5954): 
D/AndroidRuntime( 5954): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5954): CheckJNI is OFF
D/AndroidRuntime( 5954): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1031): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1930): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1031): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
V/ActivityStackEx( 1031): create ActivityStackEx
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{3886ba97 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{3886ba97 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1031): AppWindowTokenEx init.. 
E/GBMv2   (  350): DFP En is all cleared set to be enabled
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{507f238 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgeAbsQuickCoverView( 1414): mCoverXPos: 0 ,mCoverYPos: 0
D/LgeAbsQuickCoverView( 1414): mCoverWidth: 0 ,mCoverHeight: 0
I/ActivityManager( 1031): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5986 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5954): Shutting down VM
V/ActivityManager( 1031): Display changed displayId=0
D/DSDPConnection( 1839): Display #0 changed.
D/SplitWindowPolicy( 1930): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1930): topRunningActivity=ActivityInfo{c1c4461 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1930): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1930): topRunningActivity=ActivityInfo{8e4db86 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/ContextHelper( 5986): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/WebViewFactory( 5986): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 5986): Loading: webviewchromium
,I/LibraryLoader( 5986): Time to load native libraries: 11 ms (timestamps 2826-2837)
I/LibraryLoader( 5986): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5986): Binding Chromium to main looper Looper (main, tid 1) {39cbfe42}
,I/LibraryLoader( 5986): Expected native library version number "",actual native library version number ""
,I/chromium( 5986): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5986): Initializing chromium process, renderers=0
,W/art     ( 5986): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 5986): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  332): registerClient() client 0xb54f4f20, uid 10318
D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1557ea69:true
,D/BluetoothAdapter( 5986): 744459859: getState() :  mService = null. Returning STATE_OFF
W/chromium( 5986): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5986): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5986): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 5986): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5986): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5986): Build Date: 12/12/14 금
I/Adreno-EGL( 5986): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5986): Remote Branch: 
I/Adreno-EGL( 5986): Local Patches: 
I/Adreno-EGL( 5986): Reconstruct Branch: 
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 18281(824KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.861ms total 157.055ms
,W/chromium( 5986): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 5986): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5986): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5986): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5986): CordovaWebView is running on device made by: LGE
,W/art     ( 5986): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5986): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1031): Activity pause timeout for ActivityRecord{601a484 u0 com.example.hello/.MainActivity t2}
,D/OpenGLRenderer( 5986): Render dirty regions requested: true
I/OpenGLRenderer( 5986): Initialized EGL, version 1.4
D/OpenGLRenderer( 5986): Enabling debug mode 0
D/Atlas   ( 5986): Validating map...
,D/SplitWindow( 1031): check instance of lgWin Window{1d76f59b u0 com.example.hello/com.example.hello.MainActivity}
,I/SystemUI[Framework]( 1031): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1031): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1031): setLGSystemUiVisibility(0x0)
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
D/StatusBarManagerServiceEx( 1031): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2ba53fcd,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 5986): LgDataFeature() Constructor: none
,D/LgDataFeature( 5986): LgDataFeature() Constructor Done, null
I/Timeline( 5986): Timeline: Activity_idle id: android.os.BinderProxy@3a38b243 time:83294
,I/ActivityManager( 1031): Displayed com.example.hello/.MainActivity: +612ms (total +730ms)
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{601a484 u0 com.example.hello/.MainActivity t2} time:83295
I/chromium( 5986): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 5986): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 5986): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5986): 
,D/JsMessageQueue( 5986): Set native->JS mode to OnlineEventsBridgeMode
,D/InitAlarmsService( 4817): Clearing and rescheduling alarms.
,I/chromium( 5986): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5986): 
,I/ActivityManager( 1031): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6043 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 6043): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6043): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2317ccb6
,D/jxcore_app_log( 5986): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435341568
D/JX-Cordova( 5986): jxcore cordova android initializing
D/CalendarProvider2( 6043): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6043): Created com.android.providers.calendar.CalendarAlarmManager@2c5f8e53(com.android.providers.calendar.CalendarProvider2@2317ccb6)
,D/CalendarProvider2( 6043): Scheduling check of next Alarm
D/CalendarProvider2( 6043): SCHEDULE_ALARM_REMOVE
I/ActivityManager( 1031): Killing 4817:com.android.calendar/u0a13 (adj 15): empty #17
,W/jxcore-log( 5986): Initializing JXcore engine
W/jxcore-log( 5986): JXcore engine is ready
,W/jxcore-log( 5986): Starting JXcore engine
W/libprocessgroup( 1031): failed to open /acct/uid_10013/pid_4817/cgroup.procs: No such file or directory
W/m.example.hello( 5986): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8359]" dev="sockfs" ino=8359 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 5986): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/m.example.hello( 5986): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10832]" dev="sockfs" ino=10832 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 5986): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/m.example.hello( 5986): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29355]" dev="sockfs" ino=29355 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,E/GBMv2   (  350): DFP En is all cleared set to be enabled
E/GBMv2   (  350): Set value is all cleared set the max
I/GBMv2   (  350): DFP Enabled. Ignore VFP set
,W/jxcore-log( 5986): Platform android
W/jxcore-log( 5986): 
,W/jxcore-log( 5986): Process ARCH arm
W/jxcore-log( 5986): 
,I/jxcore-log( 5986): JXcore Cordova bridge is ready!
I/jxcore-log( 5986): 
W/jxcore-log( 5986): JXcore engine is started
,E/jxcore-log( 5986): >> LGE-LG-D855
E/jxcore-log( 5986): 
,I/jxcore-log( 5986): Total memory 2995761152
I/jxcore-log( 5986): 
I/jxcore-log( 5986): Free memory 639725568
I/jxcore-log( 5986): 
I/jxcore-log( 5986): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5986): 
I/jxcore-log( 5986): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5986): 
I/jxcore-log( 5986): userPath [ 'www' ]
I/jxcore-log( 5986): 
I/jxcore-log( 5986): Size 1440 2392
I/jxcore-log( 5986): 
,I/jxcore-log( 5986): Screen Brightness 50
I/jxcore-log( 5986): 
E/jxcore-log( 5986): Dummy Error Log.
E/jxcore-log( 5986): 
I/CalendarProvider2( 6043): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6043): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/jxcore-log( 5986): getBuffer is called!!!!
I/jxcore-log( 5986): 
,I/ActivityManager( 1031): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6084 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1031): Killing 5627:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10061/pid_5627/cgroup.procs: No such file or directory
W/ResourcesManager( 6084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6084): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6084): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6084): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@f08924, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@260b8c8d, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@39cbfe42, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2c5f8e53, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@293f1390, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@39316489, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@319fbc8e, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@304abcaf, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@33a9d8bc, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1cc2c045, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@fdf139a, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3d1074cb, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2399c4a8, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@4541bc1, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@308acf66, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@52f92a7, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@81a8354, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2e45b2fd, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1ce47bf2, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3a38b243, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@334680c0, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@24bf81f9, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3eba653e, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@c2a2f9f, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@3c72e8ec, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@126d44b5, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3c73974a, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@28c26bb, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@391ba7d8, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@26fa7731, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@9dbde16, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@b4c7397, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@188f6984, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@74e556d, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@39afc5a2, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1b5ab233, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@e5b99f0, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@587db69, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1be899ee, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3d043e8f, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3778651c, lg_preferences_recent_t,imezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1cb9c525, l
,D/GeneralPreferenceUtils( 6084): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,D/Config  ( 6084): [init]
,I/Config  ( 6084): LGCalendar ver.4.40.16
,I/Config  ( 6084): start check model
,I/Config  ( 6084): start check native_ca
,I/Config  ( 6084): Config Operator=OPEN, Country=EU
,D/Config  ( 6084): [setDefaultValuesToPref]
D/Config  ( 6084): [parseProfiles]
D/ProfilesParser( 6084): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6084): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6084): [updateProfiletoCountryInfo]
D/GeneralPreference( 6084): [checkAndMigrateOldPreference]
D/AlertReceiver( 6084): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6084): Start InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6084): onHandleIntent
D/HolidayDataLoader( 6084): readJsonAsset : holiday.json
,I/AlertUtils( 6084): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
D/AlertService( 6084): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6084): [updateWidgets] 
D/MonthWidgetProvider( 6084): [onReceive]
,D/CalendarWidgetProvider( 6084): [onReceive]
D/CalendarWidgetProvider( 6084): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
I/AlertUtils( 6084): [getCalendarNotiSoundURIFromCursor] getCount()= 21
D/CalendarTypeController( 6084): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6084): [onReceive]
I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
D/CalendarWidgetProvider( 6084): [onReceive]
D/CalendarWidgetProvider( 6084): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
D/CalendarTypeController( 6084): [onCreate] mContext.getPackageName() = com.android.calendar
I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,E/HolidayIntentService( 6084): onHandleIntent:holiday data empty
I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6084): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
,I/AlertUtils( 6084): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6084): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6084): End InitializeAlertRingtoneService.onHandleIntent
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 86834845178; DSPS: 2986651; Offset : -4323171762
,I/ActivityManager( 1031): Waited long enough for: ServiceRecord{2510eca9 u0 com.google.android.music/.wear.WearMetadataSyncService}
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{183c7b8b type 2 when 88706 com.android.providers.calendar} when 88706
,D/CalendarProviderBroadcastReceiver( 6043): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6043): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6043): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6043): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6043): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6043): (284) automatic index on view_events(_id)
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{2af26081 type 0 when 1448306477922 com.lge.ia.task.mrgdblogger} when 1448306477922
,D/LIA_MrGDBLogger_MrGIntentReceiverDBCleaning( 3619): [dreamwood]onReceive
D/LIA_MrGDBLogger_MrGDBCleaner( 3619): [dreamwood]onReceive
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{12f54567 type 0 when 1448306509282 com.android.vending} when 1448306509282
,D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LIA_MrGDBLogger_MrGDBManager( 3619): [dreamwood]dbFileSize : 77824
,D/LIA_MrGDBLogger_DBCleanerUtil( 3619): [dreamwood]cleanOldRecord : APP_USAGE
D/LIA_MrGDBLogger_DBCleanerUtil( 3619): [dreamwood]LimitedDate : 2015-10-24 21:21:51, count : 0
D/LIA_MrGDBLogger_DBCleanerUtil( 3619): [dreamwood]cleanOldRecord : CONCIERGE_BOARD
,D/LIA_MrGDBLogger_DBCleanerUtil( 3619): [dreamwood]LimitedDate : 2015-10-24 21:21:51, count : 0
D/LIA_MrGDBLogger_DBCleanerUtil( 3619): [dreamwood]cleanOldRecord : INFORMANT_FEATURE_STATUS_INFO
D/LIA_MrGDBLogger_DBCleanerUtil( 3619): [dreamwood]LimitedDate : 2015-10-24 21:21:51, count : 0
D/LIA_MrGDBLogger_MrGDBManager( 3619): [dreamwood]dbFileSize : 77824
D/CalendarProvider2( 6043): [IntentService] Release Lock
,D/CalendarProvider2( 6043): CalendarProviderIntentService.onDestroy()
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5768): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5768): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5768): [1] 5.onFinished: Scheduling replication attempt 1.
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1031): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService( 1031): Message: 2
,D/WifiService( 1031): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1031): setWifiEnabled: false pid=5986, uid=10318, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1031): setWifiEnabled: false pid=5986, uid=10318
E/WifiService( 1031): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 5986): ****TEST TOOK:  5053  ms ****
I/jxcore-log( 5986): 
I/jxcore-log( 5986): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5986): 
E/ThermalEngine(  342): out low battery limit. 
V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{3ae1d62d type 2 when 89962 com.google.android.gms} when 89962
D/AlertService( 6084): Beginning updateAlertNotification
D/AlertService( 6084): No fired or scheduled alerts
D/AlertService( 6084): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 6084): No events found starting within 1 week.
I/ActivityManager( 1031): Killing 5088:com.wsandroid.suite.lge/1000 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5088/cgroup.procs: No such file or directory
,D/AndroidRuntime( 6159): 
D/AndroidRuntime( 6159): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6159): CheckJNI is OFF
D/AndroidRuntime( 6159): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1031): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1031): Killing 5986:com.example.hello/u0a318 (adj 0): stop com.example.hello
I/WindowState( 1031): WIN DEATH: Window{1d76f59b u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1031): Client connection lost with reason: 4
D/InputDispatcher( 1031): Window went away: Window{1d76f59b u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings( 1031): Skipping PackageSetting{80d64a1 com.test.thalitest/10311} due to missing metadata
,I/ActivityManager( 1031):   Force finishing activity ActivityRecord{601a484 u0 com.example.hello/.MainActivity t2}
,E/GBMv2   (  350): DFP En is all cleared set to be enabled
,W/ActivityManager( 1031): Spurious death for ProcessRecord{35381762 5986:com.example.hello/u0a318}, curProc for 5986: null
I/ActivityManager( 1031): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1031):   Force finishing activity ActivityRecord{601a484 u0 com.example.hello/.MainActivity t2 f}
W/ActivityManager( 1031): Duplicate finish request for ActivityRecord{601a484 u0 com.example.hello/.MainActivity t2 f}
,I/[LGHome]EVENT( 2022): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2022): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1930): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1930): topRunningActivity=ActivityInfo{13f87c47 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2022): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2022): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/SplitWindowPolicy( 1930): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1930): topRunningActivity=ActivityInfo{1c94bc74 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
D/SplitWindowManager( 1031): removeStackAndNeedHomeResume ActivityStack{37ce00f3 stackId=1, 0 tasks}
I/[LGHome]GBoardWebView( 2022): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/ActionManagerService( 1895): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3619): handleMessage: what(1000) actionID(0x1000003)
I/InputReader( 1031): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1804): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 1984): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
D/LIA_MrGDBLogger_PackageInfoDetector( 3619): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
,W/System.err( 4171): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/System.err( 4171): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4171): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4171): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4171): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4171): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4171): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4171): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4171): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4171): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4171): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4171): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,D/SplitUIManager( 1857): split_name #11 / not available #0
D/SplitUIService( 1857): removed split : 
I/ActivityManager( 1031): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6189 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/[LGHome]LGActivityUtil( 2022): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2022): [Launcher.java:1056:onResume()]onResume end
,I/[LGHome]EVENT( 2022): [Launcher.java:1114:onPause()]onPause
I/[LGHome]GBoardWebView( 2022): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1895): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3619): handleMessage: what(1000) actionID(0x1000004)
I/[SystemUI]QSlideListController( 1469): onReceive = android.intent.action.PACKAGE_REMOVED
I/art     ( 4219): Explicit concurrent mark sweep GC freed 14761(852KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 515us total 152.583ms
V/BoardContentProvider( 3619): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
I/GBoardWebViewUtils( 2022): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2022): , create_time: 1430558575574
I/GBoardWebViewUtils( 2022): , expire_time: 0
I/GBoardWebViewUtils( 2022): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2022): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2022): , display: false
I/GBoardWebViewUtils( 2022): , animation: false }
I/GBoardWebViewUtils( 2022): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2022): , create_time: 1430558575600
I/GBoardWebViewUtils( 2022): , expire_time: 0
I/GBoardWebViewUtils( 2022): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2022): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2022): , display: false
I/GBoardWebViewUtils( 2022): , animation: false }
I/GBoardWebViewUtils( 2022): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1447937693376
I/GBoardWebViewUtils( 2022): , create_time: 1447937694406
I/GBoardWebViewUtils( 2022): , expire_time: 0
I/GBoardWebViewUtils( 2022): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1447937693376&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2022): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2022): , display: false
I/GBoardWebViewUtils( 2022): , animation: false }
,D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
D/WallpaperManager( 2022): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1469): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/SystemUI[Framework]( 1031): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1031): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1031): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1031): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2ba53fcd,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
D/SplitUIManager( 1857): split_name #11 / not available #0
I/SplitUIService( 1857): split app #11
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
I/[LGHome]GBoardWebView( 2022): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/art     ( 1031): Explicit concurrent mark sweep GC freed 15866(1100KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 2.436ms total 187.907ms
I/art     ( 1031): WaitForGcToComplete blocked for 183.402ms for cause Explicit
,D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
,D/KeyguardModel( 1469): handleShortcutListChanged...
W/ResourcesManager( 6189): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
,D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
D/administrator( 1031): Handling package changes for user 0
,W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
I/[LGHome]EVENT( 2022): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 2022): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/PluginManager( 6189): init()
D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
,D/KeyguardModel( 1469): handleShortcutListChanged...
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
I/[LGHome]Launcher.Model( 2022): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2022): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2022): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2022): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2022): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2022): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/ThermalEngine(  342): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 2962): Thermal-Lib-Client: Client request sent
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{17ba0114 u0 com.lge.launcher2/.Launcher t1} time:91641
I/NotificationService( 1031): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1031): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1031): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1031): removeObsoleteFile: deleting file=2_task.xml
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher.Model( 2022): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2022): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2022): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2022): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 2022): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2022): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2022): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2022): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/[Concierge]Service( 2600): onStartCommand(). Type : 8
D/[Concierge]Service( 2600): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2600): Update widget ID : 11
D/[Concierge]WidgetView( 2022): change position of spinner
I/art     ( 1031): Explicit concurrent mark sweep GC freed 6451(343KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.278ms total 164.814ms
D/[Concierge]Service( 2600): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2022): initWebView(). Time : 1448306514237
,I/[Concierge]WebView( 2022): Return exist ConciergeWebView. Reuse : 1026302072
D/[Concierge]WidgetView( 2022): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2022): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2022): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@151e2b47
I/[LGHome]EVENT( 2022): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2022): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2022): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2022): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2022): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2022): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
D/AndroidRuntime( 6159): Shutting down VM
,W/[Concierge]WidgetView( 2022): Widget kill message received. Destory myself. My : 1448306450877, New one : 1448306514237
D/[Concierge]WidgetView( 2022): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2022): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2022): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2022): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2022): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2022): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2022): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2022): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2022): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2022): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1031): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LgeWidgetLib]LgeAppWidgetHostView( 2022): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2022): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2022): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,I/[LGHome]EVENT( 2022): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2022): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2022): Timeline: Activity_idle id: android.os.BinderProxy@368bda03 time:91811
,W/ExternalStrings( 6189): load override strings
W/ExternalStrings( 6189): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6189): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6189): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6189): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6189): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6189): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6189): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6189): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6189): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6189): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6189): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6189): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6189): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6189): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6189): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6189): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6189): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 6189): onCreate
I/chromium( 2022): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,V/Signer  ( 6189): override build config not found
D/Signer  ( 6189): value of property debug is false
,D/LGMDMWrapper( 6189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 6189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
I/GBoardtInterface( 2022): onReloaded()
I/GBoardWebViewClient( 2022): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3619): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/LGMDMManager( 6189): Create singleton instance
V/BoardContentProvider( 3619): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1895): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3619): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3619): onEvent() : ACTION_BOARD_ENABLED
,D/ActionManagerService( 1895): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3619): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3619): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3619): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3619): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3619): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2022): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2022): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2022): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2022): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2022): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1447937693376&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2022): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1447937693376&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LGMDMWrapper( 6189): LG MDM library v4.0.0 is available on this device.
,W/ContextImpl( 6189): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 

```
