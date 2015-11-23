#### Test 5038801932cd575_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/UEI.SmartControl( 5912): Internal timer expired: 1
D/UEI.SmartControl( 5912): unbind internal service
,--------- beginning of system
I/ActivityManager( 1032): Waited long enough for: ServiceRecord{58cc521 u0 com.google.android.music/.wear.WearMetadataSyncService}
D/serial_port( 5912): close(fd = 25)
I/UEI.SmartControl( 5912): Serial port is closed.
D/AndroidRuntime( 5977): 
D/AndroidRuntime( 5977): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5977): CheckJNI is OFF
D/AndroidRuntime( 5977): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1032): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1960): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1032): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
V/ActivityStackEx( 1032): create ActivityStackEx
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{ce46bcf #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{ce46bcf #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1032): AppWindowTokenEx init.. 
E/GBMv2   (  346): DFP En is all cleared set to be enabled
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{1ef90bf0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgeAbsQuickCoverView( 1412): mCoverXPos: 0 ,mCoverYPos: 0
D/LgeAbsQuickCoverView( 1412): mCoverWidth: 0 ,mCoverHeight: 0
I/ActivityManager( 1032): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5992 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5977): Shutting down VM
V/ActivityManager( 1032): Display changed displayId=0
D/DSDPConnection( 1869): Display #0 changed.
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{2c4d59b9 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{c5bc1fe co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/ContextHelper( 5992): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/WebViewFactory( 5992): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 5992): Loading: webviewchromium
,I/LibraryLoader( 5992): Time to load native libraries: 3 ms (timestamps 8980-8983)
I/LibraryLoader( 5992): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5992): Binding Chromium to main looper Looper (main, tid 1) {223ad23a}
I/LibraryLoader( 5992): Expected native library version number "",actual native library version number ""
I/chromium( 5992): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5992): Initializing chromium process, renderers=0
W/art     ( 5992): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5992): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 5992): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5992): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5992): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  323): registerClient() client 0xb1427c20, uid 10318
D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fd351e1:true
D/BluetoothAdapter( 5992): 301293291: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 5992): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5992): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5992): Build Date: 12/12/14 금
I/Adreno-EGL( 5992): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5992): Remote Branch: 
I/Adreno-EGL( 5992): Local Patches: 
I/Adreno-EGL( 5992): Reconstruct Branch: 
W/chromium( 5992): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 5992): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5992): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5992): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5992): CordovaWebView is running on device made by: LGE
W/art     ( 5992): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5992): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5992): Render dirty regions requested: true
I/OpenGLRenderer( 5992): Initialized EGL, version 1.4
D/OpenGLRenderer( 5992): Enabling debug mode 0
D/Atlas   ( 5992): Validating map...
D/SplitWindow( 1032): check instance of lgWin Window{2736bf53 u0 com.example.hello/com.example.hello.MainActivity}
D/LgDataFeature( 5992): LgDataFeature() Constructor: none
D/LgDataFeature( 5992): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1467): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@31ce34ce,  pkg=WindowManager.LayoutParams
I/[SystemUI]NavigationThemeResource( 1467): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1467):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1467): , Keyguard show=false, IME shown=false, Panel expanded=false
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1032): Displayed com.example.hello/.MainActivity: +603ms (total +728ms)
I/Timeline( 5992): Timeline: Activity_idle id: android.os.BinderProxy@60fd8db time:79460
I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{735295c u0 com.example.hello/.MainActivity t2} time:79463
I/chromium( 5992): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 5992): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 5992): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5992): 
D/JsMessageQueue( 5992): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 5992): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5992): 
E/GBMv2   (  346): DFP En is all cleared set to be enabled
E/GBMv2   (  346): Set value is all cleared set the max
I/GBMv2   (  346): DFP Enabled. Ignore VFP set
D/jxcore_app_log( 5992): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435315456
D/JX-Cordova( 5992): jxcore cordova android initializing
W/jxcore-log( 5992): Initializing JXcore engine
W/jxcore-log( 5992): JXcore engine is ready
,W/jxcore-log( 5992): Starting JXcore engine
W/m.example.hello( 5992): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[7535]" dev="sockfs" ino=7535 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 5992): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 5992): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7697]" dev="sockfs" ino=7697 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 5992): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/m.example.hello( 5992): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[27307]" dev="sockfs" ino=27307 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 5992): Platform android
W/jxcore-log( 5992): 
W/jxcore-log( 5992): Process ARCH arm
W/jxcore-log( 5992): 
,I/jxcore-log( 5992): JXcore Cordova bridge is ready!
I/jxcore-log( 5992): 
,W/jxcore-log( 5992): JXcore engine is started
,E/jxcore-log( 5992): >> LGE-LG-D855
E/jxcore-log( 5992): 
,I/jxcore-log( 5992): Total memory 2995761152
I/jxcore-log( 5992): 
I/jxcore-log( 5992): Free memory 661598208
I/jxcore-log( 5992): 
I/jxcore-log( 5992): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5992): 
I/jxcore-log( 5992): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5992): 
I/jxcore-log( 5992): userPath [ 'www' ]
I/jxcore-log( 5992): 
I/jxcore-log( 5992): Size 1440 2392
I/jxcore-log( 5992): 
I/jxcore-log( 5992): Screen Brightness 50
I/jxcore-log( 5992): 
E/jxcore-log( 5992): Dummy Error Log.
E/jxcore-log( 5992): 
,I/jxcore-log( 5992): getBuffer is called!!!!
I/jxcore-log( 5992): 
,D/InitAlarmsService( 4878): Clearing and rescheduling alarms.
,I/ActivityManager( 1032): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6077 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 6077): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6077): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@260ed12e
,D/CalendarProvider2( 6077): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6077): Created com.android.providers.calendar.CalendarAlarmManager@11f55eeb(com.android.providers.calendar.CalendarProvider2@260ed12e)
D/CalendarProvider2( 6077): Scheduling check of next Alarm
D/CalendarProvider2( 6077): SCHEDULE_ALARM_REMOVE
I/ActivityManager( 1032): Killing 4878:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10013/pid_4878/cgroup.procs: No such file or directory
,I/CalendarProvider2( 6077): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6077): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager( 1032): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6113 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1032): Killing 5196:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5196/cgroup.procs: No such file or directory
,W/ResourcesManager( 6113): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6113): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6113): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6113): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@14e18e5c, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1491d565, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@223ad23a, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@11f55eeb, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3d273448, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@334f62e1, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@23f3d806, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3548fec7, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@29f4cf4, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1ffe4c1d, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@15e56e92, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@114cc063, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2fde4460, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1cb88d19, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2fe7e1de, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1c40ffbf, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2253468c, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@193be1d5, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3d0c3dea, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@60fd8db, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3d343f78, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@965c651, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@36684eb6, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@92927b7, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1f29db24, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@276f768d, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3ea2a042, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2d1e8853, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@6bb8590, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1de9ee89, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@a3e7e8e, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@16ff56af, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@117b6abc, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1579ea45, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@a7f59a, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@374aecb, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1f276a8, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2253e5c1, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@21ffd166, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@69d6ca7, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@384c5554, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@d781cfd, 
D/GeneralP,referenceUtils( 6113): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6113): [init]
,I/Config  ( 6113): LGCalendar ver.4.40.16
I/Config  ( 6113): start check model
I/Config  ( 6113): start check native_ca
I/Config  ( 6113): Config Operator=OPEN, Country=EU
D/Config  ( 6113): [setDefaultValuesToPref]
D/Config  ( 6113): [parseProfiles]
D/ProfilesParser( 6113): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6113): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6113): [updateProfiletoCountryInfo]
,D/GeneralPreference( 6113): [checkAndMigrateOldPreference]
D/AlertReceiver( 6113): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6113): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6113): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6113): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,W/HolidayIntentService( 6113): onHandleIntent
,D/HolidayDataLoader( 6113): readJsonAsset : holiday.json
D/AlertService( 6113): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6113): [updateWidgets] 
,D/MonthWidgetProvider( 6113): [onReceive]
D/CalendarWidgetProvider( 6113): [onReceive]
D/CalendarWidgetProvider( 6113): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6113): [onCreate] mContext.getPackageName() = com.android.calendar
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 17215(794KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 2.512ms total 156.531ms
I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
D/WeekWidgetProvider( 6113): [onReceive]
D/CalendarWidgetProvider( 6113): [onReceive]
D/CalendarWidgetProvider( 6113): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
D/CalendarTypeController( 6113): [onCreate] mContext.getPackageName() = com.android.calendar
,I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
E/HolidayIntentService( 6113): onHandleIntent:holiday data empty
I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6113): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6113): set default noti to content://media/internal/audio/media/41
,I/InitNotificationRingtoneService( 6113): End InitializeAlertRingtoneService.onHandleIntent
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1032): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService( 1032): Message: 2
D/WifiService( 1032): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1032): setWifiEnabled: false pid=5992, uid=10318, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1032): setWifiEnabled: false pid=5992, uid=10318
E/WifiService( 1032): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 5992): ****TEST TOOK:  5070  ms ****
I/jxcore-log( 5992): 
I/jxcore-log( 5992): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5992): 
D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=633217859, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{9859dc0 type 2 when 87286 com.android.providers.calendar} when 87286
,D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/CalendarProviderBroadcastReceiver( 6077): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6077): [IntentService] WakeLock acquire, start IntentSerivce
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=633217859 [*alarm*], flags=0x0
,D/CalendarProvider2( 6077): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6077): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6077): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6077): (284) automatic index on view_events(_id)
V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{915b09f type 0 when 1448315235159 com.android.vending} when 1448315235159
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CalendarProvider2( 6077): [IntentService] Release Lock
,D/CalendarProvider2( 6077): CalendarProviderIntentService.onDestroy()
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,D/AndroidRuntime( 6166): 
D/AndroidRuntime( 6166): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6166): CheckJNI is OFF
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AndroidRuntime( 6166): Calling main entry com.android.commands.pm.Pm
,W/PackageSettings( 1032): Skipping PackageSetting{3f2721f9 com.test.thalitest/10311} due to missing metadata
,I/ActivityManager( 1032): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1032): Killing 5992:com.example.hello/u0a318 (adj 0): stop com.example.hello
I/WindowState( 1032): WIN DEATH: Window{2736bf53 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1032): Client connection lost with reason: 4
D/InputDispatcher( 1032): Window went away: Window{2736bf53 u0 com.example.hello/com.example.hello.MainActivity}
,I/ActivityManager( 1032):   Force finishing activity ActivityRecord{735295c u0 com.example.hello/.MainActivity t2}
,E/GBMv2   (  346): DFP En is all cleared set to be enabled
I/ActivityManager( 1032): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1032):   Force finishing activity ActivityRecord{735295c u0 com.example.hello/.MainActivity t2 f}
W/ActivityManager( 1032): Duplicate finish request for ActivityRecord{735295c u0 com.example.hello/.MainActivity t2 f}
W/ActivityManager( 1032): Spurious death for ProcessRecord{34df9aa2 5992:com.example.hello/u0a318}, curProc for 5992: null
I/[LGHome]EVENT( 2083): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2083): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{a12d5f co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2083): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{16ed73ac co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
D/SplitWindowManager( 1032): removeStackAndNeedHomeResume ActivityStack{1f9e6333 stackId=1, 0 tasks}
D/ActionManagerService( 1920): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 2721): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2083): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1467): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1032): Reconfiguring input devices.  changes=0x00000010
D/LIA_MrGDBLogger_PackageInfoDetector( 2721): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
D/LIA_Service_RemotePackageHandler( 2027): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
W/GeofencerStateMachine( 1834): Ignoring removeGeofence because network location is disabled.
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/System.err( 4194): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 4194): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4194): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4194): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4194): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4194): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4194): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4194): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4194): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4194): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4194): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4194): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1032): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6207 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/[LGHome]EVENT( 2083): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2083): [Launcher.java:1114:onPause()]onPause
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BoardContentProvider( 2721): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2083): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2083): , create_time: 1430558575574
I/GBoardWebViewUtils( 2083): , expire_time: 0
I/GBoardWebViewUtils( 2083): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2083): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2083): , display: false
I/GBoardWebViewUtils( 2083): , animation: false }
I/GBoardWebViewUtils( 2083): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2083): , create_time: 1430558575600
I/GBoardWebViewUtils( 2083): , expire_time: 0
I/GBoardWebViewUtils( 2083): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2083): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2083): , display: false
I/GBoardWebViewUtils( 2083): , animation: false }
I/GBoardWebViewUtils( 2083): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1447937693376
I/GBoardWebViewUtils( 2083): , create_time: 1447937694406
I/GBoardWebViewUtils( 2083): , expire_time: 0
I/GBoardWebViewUtils( 2083): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1447937693376&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2083): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2083): , display: false
I/GBoardWebViewUtils( 2083): , animation: false }
I/[SystemUI]QSlideListController( 1467): onReceive = android.intent.action.PACKAGE_REMOVED
D/ActionManagerService( 1920): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2721): handleMessage: what(1000) actionID(0x1000004)
D/SplitUIManager( 1886): split_name #11 / not available #0
D/WallpaperManager( 2083): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/SplitUIService( 1886): removed split : 
I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@31ce34ce,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1467): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1467): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
D/administrator( 1032): Handling package changes for user 0
D/SplitUIManager( 1886): split_name #11 / not available #0
I/SplitUIService( 1886): split app #11
D/KeyguardModel( 1467): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1467): createShortcutInfo...
D/KeyguardModel( 1467): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/Finsky  ( 5784): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5784): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5784): [1] 5.onFinished: Scheduling replication attempt 1.
I/art     ( 4239): Explicit concurrent mark sweep GC freed 15559(910KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 729us total 236.375ms
D/KeyguardModel( 1467): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1467): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1467): createShortcutInfo...
I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
W/ResourcesManager( 1467): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2083): [Launcher.java:5349:onStop()]onStop
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1467): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1467): createShortcutInfo...
D/KeyguardModel( 1467): handleShortcutListChanged...
D/KeyguardModel( 1467): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1467): createShortcutInfo...
D/KeyguardModel( 1467): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1467): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1467): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1467): createShortcutInfo...
W/ResourceType( 1467): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1467): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1467): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1467): createShortcutInfo...
D/KeyguardModel( 1467): handleShortcutListChanged...
W/ResourcesManager( 6207): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
D/PluginManager( 6207): init()
I/NotificationService( 1032): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1032): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1032): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1467): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
D/TaskPersister( 1032): removeObsoleteFile: deleting file=2_task.xml
I/[SystemUI]NavigationThemeResource( 1467): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1467):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1467): , Keyguard show=false, IME shown=false, Panel expanded=false
I/art     ( 1032): Explicit concurrent mark sweep GC freed 18502(1239KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 9.756ms total 360.140ms
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
D/AndroidRuntime( 6166): Shutting down VM
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{6ddfe5f u0 com.lge.launcher2/.Launcher t1} time:88685
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2083): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2083): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2083): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2612): onStartCommand(). Type : 8
D/[Concierge]Service( 2612): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2612): Update widget ID : 11
D/[Concierge]WidgetView( 2083): change position of spinner
I/[Concierge]WidgetView( 2083): initWebView(). Time : 1448315238357
D/[Concierge]Service( 2612): onStartCommand(). Type : 0
I/[Concierge]WebView( 2083): Return exist ConciergeWebView. Reuse : 148068586
D/[Concierge]WidgetView( 2083): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2083): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2083): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@55bb550
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2083): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2083): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2083): Widget kill message received. Destory myself. My : 1448315177848, New one : 1448315238357
D/[Concierge]WidgetView( 2083): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2083): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 2083): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/ResourceType( 1032): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/AlertService( 6113): Beginning updateAlertNotification
E/[LgeWidgetLib]LgeAppWidgetHostView( 2083): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AlertService( 6113): No fired or scheduled alerts
I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/AlertService( 6113): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/Timeline( 2083): Timeline: Activity_idle id: android.os.BinderProxy@1137589b time:88882
D/AlarmScheduler( 6113): No events found starting within 1 week.
I/ActivityManager( 1032): Killing 5649:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10061/pid_5649/cgroup.procs: No such file or directory
I/chromium( 2083): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
W/ExternalStrings( 6207): load override strings
W/ExternalStrings( 6207): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6207): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6207): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6207): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6207): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6207): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6207): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6207): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6207): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6207): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6207): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6207): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6207): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6207): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6207): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6207): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6207): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6207): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)

```
