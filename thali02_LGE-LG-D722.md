#### Test 57617811ecc172f_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  904): Killing 5106:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  904): failed to open /acct/uid_10023/pid_5106/cgroup.procs: No such file or directory
,--------- beginning of main
D/UEI.SmartControl( 5057): Internal timer expired: 1
D/AndroidRuntime( 5312): 
D/AndroidRuntime( 5312): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5312): CheckJNI is OFF
D/AndroidRuntime( 5312): Calling main entry com.android.commands.am.Am
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  904): setTaskToReturnTo : TaskRecord{40c25a0 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  904): setTaskToReturnTo : TaskRecord{40c25a0 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  904): AppWindowTokenEx init.. 
D/ContextHelper(  904): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  904): Focus left window: Window{34423f0d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5312): Shutting down VM
D/SplitWindow(  904): check instance of lgWin Window{839152a u0 Starting com.test.thalitest}
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5327 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1936): Closing mic
I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  904): Starting window displayed
I/SystemUI[Framework](  904): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  904): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  904): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  904): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  904): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a5ea9cc,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  904): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1373): draw background and invalidate : color = e000000
I/MicrophoneInputStream( 1936): mic_close com.google.android.apps.gsa.speech.audio.u@2af7855a
V/AudioRecord( 1936): stop()
D/AudioRecord( 1936): AudioRecord->stop()
V/AudioFlinger(  286): RecordHandle::stop()
V/AudioFlinger(  286): RecordThread::stop
V/AudioFlinger(  286): Record stopped OK
V/AudioPolicyManager(  286): stopInput() input 17
V/AudioPolicyService(  286): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  286): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  286): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  286): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  286): ThreadBase::setParameters() routing=0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
D/BarTransitions( 1373): draw background and invalidate : color = f0e0e0e
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
,V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb386d000
D/audio_hw_primary(  286): in_standby: enter: stream (0xb3849200) usecase(7: audio-record)
V/audio_hw_primary(  286): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  286): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  286): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  286): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  286): disable_audio_route: exit
E/audio_hw_primary(  286): disable_snd_device: enter 144
D/hardware_info(  286): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  286): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  286): stop_input_stream: exit: status(0)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  286): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  286): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  286): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyService(  286): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  286): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  286): setParameters(): io 17, keyvalue hotword_active=0, calling pid 286
V/AudioFlinger(  286): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  286): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  286): in_set_parameters: exit: status(0)
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb386d000
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioFlinger(  286): RecordHandle::stop()
V/AudioFlinger(  286): RecordThread::stop
V/AudioPolicyManager(  286): releaseInput() 17
V/AudioPolicyManager(  286): closeInput(17)
V/AudioFlinger(  286): closeInput() 17
V/AudioSystem(  286): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): ThreadBase::exit
V/AudioSystem( 1936): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3113): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2781): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioSystem(  904): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): RecordThread 0xb386d000 exiting
D/audio_hw_primary(  286): adev_close_input_stream: enter:stream_handle(0xb3849200)
D/audio_hw_primary(  286): in_standby: enter: stream (0xb3849200) usecase(7: audio-record)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioPolicyService(  286): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  286): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioSystem( 1743): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  286): AudioCommandThread() processing update audio port list
V/AudioPolicyManager(  286): releaseInput() exit
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioFlinger(  286): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  286): removeClient_l() pid 1936, calling pid 286
V/AudioFlinger(  286): releasing 16 from 1936 for -1
V/AudioFlinger(  286):  decremented refcount to 0
V/AudioFlinger(  286): purging stale effects
I/HotwordRecognitionRnr( 1936): Stopping hotword detection.
I/HotwordRecognitionRnr( 1936): Hotword detection finished
D/ContextHelper( 5327): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5327): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5327): Time to load native libraries: 2 ms (timestamps 1856-1858)
I/LibraryLoader( 5327): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5327): Binding Chromium to main looper Looper (main, tid 1) {6503a82}
I/LibraryLoader( 5327): Expected native library version number "",actual native library version number ""
I/chromium( 5327): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5327): Initializing chromium process, singleProcess=true
W/art     ( 5327): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5327): ApplicationContext is null in ApplicationStatus
W/chromium( 5327): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5327): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5327): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5327): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5327): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5327): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5327): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5327): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5327): Remote Branch: 
I/Adreno-EGL( 5327): Local Patches: 
I/Adreno-EGL( 5327): Reconstruct Branch: 
V/AudioPolicyService(  286): registerClient() client 0xb551cd00, uid 10316
D/BluetoothManagerService(  904): Message: 20
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@167deffc:true
D/BluetoothAdapter( 5327): 874556805: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5327): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5327): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5327): CordovaWebView is running on device made by: LGE
,W/art     ( 5327): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5327): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5327): Activity.onPostResume() called 
,D/OpenGLRenderer( 5327): Render dirty regions requested: true
I/OpenGLRenderer( 5327): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5327): Enabling debug mode 0
D/Atlas   ( 5327): Validating map...
,D/SplitWindow(  904): check instance of lgWin Window{111b502c u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5327): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  904): Focus entered window: Window{111b502c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  904): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/Timeline( 5327): Timeline: Activity_idle id: android.os.BinderProxy@3676b57e time:82497
,I/ActivityManager(  904): Displayed com.test.thalitest/.MainActivity: +1s71ms
I/Timeline(  904): Timeline: Activity_windows_visible id: ActivityRecord{2662f559 u0 com.test.thalitest/.MainActivity t222} time:82500
I/CheckinService( 4023): Done disabling old GoogleServicesFramework version
W/BindingManager( 5327): Cannot call determinedVisibility() - never saw a connection for the pid: 5327
,D/InitAlarmsService( 3554): Clearing and rescheduling alarms.
,W/art     ( 5233): Suspending all threads took: 5.590ms
,I/ActivityManager(  904): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5390 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5390): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5390): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@b8d2d91
,D/CalendarProvider2( 5390): [getOrCreateCalendarAlarmManager]
D/JsMessageQueue( 5327): Set native->JS mode to OnlineEventsBridgeMode
,I/CalendarProvider2( 5390): Created com.android.providers.calendar.CalendarAlarmManager@6503a82(com.android.providers.calendar.CalendarProvider2@b8d2d91)
D/CalendarProvider2( 5390): Scheduling check of next Alarm
D/CalendarProvider2( 5390): SCHEDULE_ALARM_REMOVE
,I/ActivityManager(  904): Killing 3554:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  904): failed to open /acct/uid_10013/pid_3554/cgroup.procs: No such file or directory
,I/GAV2    ( 5233): Thread[GAThread,5,main]: No campaign data found.
,D/jxcore_app_log( 5327): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426160128
,I/chromium( 5327): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 5327): CheckpointMarkThreadRoots callback created = 0x9905ccc0
,I/art     ( 5327): CheckpointMarkThreadRoots callback created = 0x9905cc90
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/CalendarProvider2( 5390): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5390): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  904): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5425 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 5140:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  904): failed to open /acct/uid_10018/pid_5140/cgroup.procs: No such file or directory
W/ResourcesManager( 5425): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 5425): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 5425): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 5425): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@35ef00f7, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3f18db64, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3c611cd, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@6503a82, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2488b593, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@383a49d0, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1a2efdc9, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@9cb7cce, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@ff17ef, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@17c232fc, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3420ad85, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@20a697da, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@35cf440b, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3b7d82e8, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@39c39d01, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@21e657a6, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@e2c15e7, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@f1be594, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@134c083d, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3e104832, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2b9a2983, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@279bc700, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3df5eb39, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3676b57e, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@394bdadf, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2976532c, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@34c101f5, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3d44ab8a, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@393d45fb, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@258b7618, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@28ecc871, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@a49f656, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@71046d7, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@18cddbc4, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@6347aad, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@308721e2, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2ca87973, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3aaef030, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3ecb14a9, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@797a2e, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@248739cf, lg_preferences_recent_,timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@64adf5c, l
D/GeneralPreferenceUtils( 5425): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,D/Config  ( 5425): [init]
I/Config  ( 5425): LGCalendar ver.4.40.17
I/Config  ( 5425): start check model
I/Config  ( 5425): start check native_ca
I/Config  ( 5425): Config Operator=OPEN, Country=EU
D/Config  ( 5425): [setDefaultValuesToPref]
D/Config  ( 5425): [parseProfiles]
D/ProfilesParser( 5425): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5425): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5425): [updateProfiletoCountryInfo]
D/GeneralPreference( 5425): [checkAndMigrateOldPreference]
,D/AlertReceiver( 5425): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 5425): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 5425): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
W/HolidayIntentService( 5425): onHandleIntent
D/HolidayDataLoader( 5425): readJsonAsset : holiday.json
,I/AlertUtils( 5425): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,D/AlertService( 5425): 0 Action = android.intent.action.PROVIDER_CHANGED
I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
E/AgendaWidgetManager( 5425): [updateWidgets] 
D/MonthWidgetProvider( 5425): [onReceive]
,D/CalendarWidgetProvider( 5425): [onReceive]
D/CalendarWidgetProvider( 5425): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
D/CalendarTypeController( 5425): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 5425): onHandleIntent:holiday data empty
,I/art     (  904): Explicit concurrent mark sweep GC freed 13493(728KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.660ms total 152.758ms
,D/WeekWidgetProvider( 5425): [onReceive]
D/CalendarWidgetProvider( 5425): [onReceive]
D/CalendarWidgetProvider( 5425): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5425): [onCreate] mContext.getPackageName() = com.android.calendar
I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5425): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5425): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 5425): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 5425): End InitializeAlertRingtoneService.onHandleIntent
,W/jxcore-log( 5327): Initializing JXcore engine
,W/jxcore-log( 5327): JXcore engine is ready
W/Thread-636( 5418): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[4932]" dev="sockfs" ino=4932 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-636( 5418): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-636( 5418): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6842]" dev="sockfs" ino=6842 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-636( 5418): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-636( 5418): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-636( 5418): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[24188]" dev="sockfs" ino=24188 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5327): Starting JXcore engine
,W/jxcore-log( 5327): Platform android
W/jxcore-log( 5327): 
W/jxcore-log( 5327): Process ARCH arm
W/jxcore-log( 5327): 
,I/jxcore-log( 5327): JXcore Cordova bridge is ready!
I/jxcore-log( 5327): 
W/jxcore-log( 5327): JXcore engine is started
,I/jxcore-log( 5327): Toggling radios to true
I/jxcore-log( 5327): 
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  904): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  904): Message: 1
D/BluetoothManagerService(  904): MESSAGE_ENABLE: mBluetooth = null
D/BluetoothAdapterService(164330702)( 1985): onBind()
,D/WifiServiceImplEx(  904): setWifiEnabled: true pid=5327, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/BluetoothManagerService(  904): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  904): Message: 40
D/BluetoothManagerService(  904): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/WifiService(  904): setWifiEnabled: true pid=5327, uid=10316
D/LocationManagerService(  904): getAllProviders()=[passive, gps, network]
,D/Ulp_jni (  904): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,D/Ulp_jni (  904): JNI:system_update. Event-4
D/LocationManagerService(  904): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  904): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  904): JNI:system_update. Event-4
D/WifiServiceImplEx(  904): disconnect pid=5327, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  904): reconnect pid=5327, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5327): Radios toggled
I/jxcore-log( 5327): 
I/jxcore-log( 5327): My device name is: LGE-LG-D722
I/jxcore-log( 5327): 
I/LGFTMITEM(  904): [GET_FTM][id=6], offset=12288
,E/WifiHW  (  904): Wifi MAC Address = a0:39:f7:70:12:80
I/bluedroid( 1985): config_hci_snoop_log
E/WifiHW  (  904): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  904): band=b
E/WifiHW  (  904): ": cur_etheraddr=a0:39:f7:70:12:80
D/SoftapController(  281): Softap fwReload - Ok
,D/BluetoothManagerService(  904): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  904): Broadcasting onBluetoothServiceUp() to 9 receivers.
V/LGMDMManagerInternal( 1985): Create singleton instance
,D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  281): Setting iface cfg
D/CommandListener(  281): Trying to bring down wlan0
D/CommandListener(  281): Clearing all IP addresses on wlan0
,E/WifiHW  (  904): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
I/wpa_supplicant( 5472): Successfully initialized wpa_supplicant
,D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): enable() - Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1985): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 1985): Setting state to 11
I/BluetoothAdapterState( 1985): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(164330702)( 1985): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  904): Message: 60
D/BluetoothManagerService(  904): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  904): Bluetooth State Change Intent: 10 -> 11
D/WifiMonitor(  904): startMonitoring(wlan0) with mConnected = false
D/BluetoothAdapterService(164330702)( 1985): processStart()
,D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:09.831 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
,I/wpa_supplicant( 5472): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 5472): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,I/ActivityManager(  904): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5478 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/LGBluetoothAPIService( 1806): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BtSettings.ProfileConfig( 1985): Unable to read settings
D/BtSettings.ProfileConfig( 1985): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1985): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1985): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1985): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1985): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 1985): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1985): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1985): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1985): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1985): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1985): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/WifiServerServiceExt(  904): WIFI_STATE_CHANGED_ACTION [2]
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.WIFI_STATE_CHANGED at null
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
,W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): processStart() - Make Bond State Machine
D/BluetoothBondStateMachine( 1985): make
,D/BluetoothAdapterService( 1985): setAdapterService() - set to: null
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
D/LGBluetoothServiceAdapter( 1985): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 1985): StableState(): Entering Off State
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1985): Unable to read settings
D/BtSettings.ProfileConfig( 1985): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1985): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1985): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1985): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1985): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1985): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 1985): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1985): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1985): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1985): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1985): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1985): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
,D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
,I/[SystemUI]BluetoothHandler( 1373): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
D/HeadsetService( 1985): Received start request. Starting profile...
D/BluetoothHeadset( 1743): Proxy object connected
D/BluetoothHeadset(  904): Proxy object connected
,I/LGBluetoothHeadsetServiceJni( 1985): classInitNative: succeeds
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
D/LGBluetoothFeatureConfig( 1985): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 1985): classInitNative: succeeds
D/BluetoothHeadset( 1743): Proxy object connected
D/HeadsetStateMachine( 1985): make
,D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1985): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
D/BluetoothHeadset( 1743): Proxy object connected
,D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1985): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
I/art     ( 1373): Background sticky concurrent mark sweep GC freed 778(37KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 31MB/31MB, paused 25.371ms total 89.069ms
,D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
,W/BluetoothAdapterService( 1985): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
V/LGMDMManager( 1985): Create singleton instance
I/BluetoothAdapterState( 1985): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetStateMachine( 1985): max_hf_connections = 1
I/bluedroid( 1985): get_profile_interface handsfree
,I/bt-btif ( 1985): btif_hf_get_interface
I/bt-btif ( 1985): init
D/bt-btif ( 1985): max_hf_clients = 1
D/bt-btif ( 1985): btif_max_hf_clients = 1
D/bt-btif ( 1985): btif_enable_service: current services:0xa0632330
V/ToneGenerator( 1985): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  286): registerClient() client 0xb551c880, uid 1002
V/AudioPolicyManager(  286): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  286): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  286): getOutput() returns output 2
V/AudioFlinger(  286): registerClient() client 0xb40330d0, pid 1985
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  286): thread 0xb5651000 type 0 TID 1291 waking up
V/AudioFlinger(  286): thread 0xb56eb000 type 0 TID 1295 waking up
V/AudioFlinger(  286): thread 0xb5735000 type 0 TID 1297 waking up
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
V/AudioFlinger(  286): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioSystem(  286): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  286): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem(  904): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  904): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1985): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1373): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1985): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1373): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2781): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2781): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
V/AudioFlinger(  286): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioSystem(  286): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  286): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1743): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1743): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1373): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1373): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1985): ioConfigChanged() event 0, ioHandle 4
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem( 1985): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 2781): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2781): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3113): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  904): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  904): ioConfigChanged() opening already existing output! 4
,V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
V/AudioFlinger(  286): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem(  286): ioConfigChanged() event 0, ioHandle 6,
V/AudioSystem(  286): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1373): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1373): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem( 3113): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1936): ioConfigChanged() event 0, ioHandle 2
,V/AudioSystem( 1936): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3113): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1743): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3113): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1743): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1743): ioConfigChanged() event 0, ioHandle 6
,V/AudioSystem( 1743): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 3113): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3113): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  904): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  904): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1985): ioConfigChanged() event 0, ioHandle 6
,V/AudioSystem( 1985): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem( 2781): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2781): ioConfigChanged() opening already existing output! 6
W/ResourcesManager( 5478): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/AudioSystem( 1936): ioConfigChanged() event 0, ioHandle 4
V/ToneGenerator( 1985): Create Track: 0xb4909480
V/AudioTrack( 1985): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
,V/AudioTrack( 1985): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
,I/AudioFlinger(  286): isAudioPlaybackHookOn() false
D/AudioTrack( 1985): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioSystem( 1936): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1936): ioConfigChanged() event 0, ioHandle 6
V/AudioPolicyManager(  286): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioSystem( 1936): ioConfigChanged() opening already existing output! 6
V/AudioPolicyManager(  286): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  286): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  286): getOutput() returns output 2
V/AudioSystem( 1985): getLatency() output 2, latency 50
V/AudioSystem( 1985): getFrameCount() output 2, frameCount 960
V/AudioTrack( 1985): createTrack_l() output 2 afLatency 50
V/AudioTrack( 1985): Create normal PCM 0x1 Track
W/ResourcesManager( 5478): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5478): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5478): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/AudioFlinger(  286): createTrack() lSessionId: 22
V/AudioFlinger(  286): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
W/ResourcesManager( 5478): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 1
V/AudioTrack( 1985): Flags here  0x4 
V/AudioTrack( 1985): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  286): acquiring 22 from 1985, for 1985
V/AudioFlinger(  286):  added new entry for 22
V/ToneGenerator( 1985): ToneGenerator INIT OK, time: 86583
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb5651000
,D/HeadsetStateMachine( 1985): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 1985): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1985): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1985): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  286): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1985
D/audio_hw_primary(  286): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  286): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: exit
V/voice   (  286): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  286): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  286): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  286): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  286): lge_platform_set_loopback_parameters: enter: 
,D/audio_hw_extn(  286): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  286): adev_set_parameters: exit with code(0)
V/ToneGenerator( 1985): ToneGenerator destructor
V/ToneGenerator( 1985): stopTone
V/ToneGenerator( 1985): Delete Track: 0xb4909480
V/AudioTrack( 1985): ~AudioTrack, releasing session id from 1985 on behalf of 1985
V/AudioFlinger(  286): remove track (4099) and delete from mixer
V/AudioPolicyService(  286): AudioCommandThread() adding release output 2
V/AudioPolicyService(  286): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  286): releasing 22 from 1985 for 1985
V/AudioFlinger(  286):  decremented refcount to 0
V/AudioFlinger(  286): purging stale effects
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  286): releaseOutput() 2
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioFlinger(  286): PlaybackThread::Track destructor
V/AudioFlinger(  286): removeClient_l() pid 1985, calling pid 286
I/art     ( 1373): Background partial concurrent mark sweep GC freed 6014(287KB) AllocSpace objects, 45(8MB) LOS objects, 39% free, 23MB/38MB, paused 1.809ms total 107.723ms
,I/ActivityManager(  904): Process com.android.vending (pid 5187) has died
,D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
D/BluetoothA2dp(  904): Proxy object connected
D/A2dpService( 1985): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 1985): classInitNative: succeeds
V/Avrcp   ( 1985): make
D/Avrcp   ( 1985): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 1985): get_profile_interface avrcp
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/bt-btif ( 1985): btif_rc_get_interface
I/bt-btif ( 1985): ## init ##
I/IndexDatabaseHelper( 5478): Using schema version: 115
,I/IndexDatabaseHelper( 5478): Index is fine
I/LGBluetoothAvrcpServiceJni( 1985): classInitNative: succeeds
I/LGBluetoothAvrcpAdapter( 1985): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 1985): initNative: succeeds
I/BluetoothAvrcpBrcmAdapterJni( 1985): classInitBrcmNative
I/BluetoothAvrcpBrcmAdapterJni( 1985): initBrcmNative
V/AudioService(  904): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,E/AudioService(  904): No RCC entry present to update
E/RemoteController( 1985): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 1985): classInitNative
I/BluetoothA2dpServiceJni( 1985): classInitNative: succeeds
D/A2dpStateMachine( 1985): make
I/bluedroid( 1985): get_profile_interface a2dp
I/bt-btif ( 1985): btif_av_get_src_interface
I/bt-btif ( 1985): init
D/bt-btif ( 1985): btif_enable_service: current services:0xa0632330
I/LGBluetoothA2dpServiceJni( 1985): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1985): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 1985): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 1985): [BTUI] init
D/LGBluetoothPowerControlManager( 1985): [BTUI] init : getProfileProxy
D/BluetoothManagerService(  904): Message: 30
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
I/BluetoothHidServiceJni( 1985): classInitNative: succeeds
D/A2dpStateMachine( 1985): Enter Disconnected: -2
,D/HidService( 1985): Received start request. Starting profile...
I/bluedroid( 1985): get_profile_interface hidhost
I/bt-btif ( 1985): btif_hh_get_interface
I/bt-btif ( 1985): init
D/bt-btif ( 1985): btif_enable_service: current services:0xa0632330
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
I/BluetoothHealthServiceJni( 1985): classInitNative: succeeds
D/HealthService( 1985): Received start request. Starting profile...
I/bluedroid( 1985): get_profile_interface health
I/bt-btif ( 1985): btif_hl_get_interface
I/bt-btif ( 1985): init
D/bt-btif ( 1985): Process name (droid.bluetooth)
D/bt-btif ( 1985): btif_hl_soc_thread_init
D/bt-btif ( 1985): create_thread: entered
D/bt-btif ( 1985): create_thread: thread created successfully
D/bt-btif ( 1985): entered btif_hl_select_thread
D/bt-btif ( 1985): btif_hl_select_wakeup_init
D/bt-btif ( 1985): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 1985): max_s=55 
D/bt-btif ( 1985): set curr_set = org_set 
I/LGBluetoothHealthServiceJni( 1985): classInitNative: succeeds
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
I/BluetoothPanServiceJni( 1985): classInitNative(L105): succeeds
D/PanService( 1985): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1985): initializeNative(L110): pan
I/bluedroid( 1985): get_profile_interface pan
D/bt-btif ( 1985): stack_initialized = 0, btpan_cb.enabled:0
,I/LGBluetoothPanAdapter( 1985): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
I/BtGatt.JNI( 1985): classInitNative(L901): classInitNative: Success!
,D/BtGatt.DebugUtils( 1985): handleDebugAction() action=null
D/BtGatt.GattService( 1985): Received start request. Starting profile...
D/BtGatt.GattService( 1985): start()
I/bluedroid( 1985): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 1985): advertise manager created
I/LGBluetoothGattAdapter( 1985): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 1985): setGattService:  set to: null
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
,I/LGBluetoothMapAdapter( 1985): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1985): BluetoothMapBinder()
D/BluetoothMapService( 1985): Received start request. Starting profile...
D/BluetoothMapService( 1985): start()
D/BluetoothMapEmailSettingsLoader( 1985): Found 0 applications
D/BluetoothMapEmailAppObserver( 1985): createReceiver()
D/BluetoothMapEmailAppObserver( 1985): initObservers()
,D/BluetoothMapEmailAppObserver( 1985): getEnabledAccountItems()
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
I/BluetoothSAPServiceJni( 1985): classInitNative(L170): succeeds
D/SapService( 1985): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1985): initializeNative(L175): sap
I/bluedroid( 1985): get_profile_interface sap
I/bt-btif ( 1985): btif_sc_get_interface
I/bt-btif ( 1985): init
D/bt-btif ( 1985): btif_enable_service: current services:0xa0632330
I/LGBluetoothSapAdapter( 1985): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1985): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1985): [BTUI] initSapManager
,D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
D/LgeBluetoothSimManager( 1743): [BTUI] SAP_ENABLE_EVT
V/BluetoothFTPServiceJni( 1985): classInitNative
I/BluetoothFTPServiceJni( 1985): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
,D/BluetoothFTPService( 1985): BluetoothFtpBinder()
D/**BluetoothFTPService( 1985): Received start request. Starting profile...
V/BluetoothFTPService( 1985): FTP-Server Service start
D/BluetoothFTPServiceJni( 1985): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1985): get_profile_interface ftp
I/bt-btif ( 1985): btif_fts_get_interface
I/bt-btif ( 1985): init
D/bt-btif ( 1985): btif_enable_service: current services:0xa0632330
D/BluetoothFTPServiceJni( 1985): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
D/LGBluetoothFeatureConfig( 1985): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 1985): classInitNative
I/BluetoothOPPServiceJni( 1985): classInitNative(L373): succeeds
V/OppService( 1985): Opp initBinder
D/**OppService( 1985): Received start request. Starting profile...
D/OppService( 1985): Starting OppService 
D/LGBluetoothOppAdapter( 1985): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/NotificationManager( 1985): com.android.bluetooth: cancelAll by com.android.bluetooth
,V/BluetoothOppNotification( 1985): send message
D/BluetoothOppPreference( 1985): Dumping Names:  
D/BluetoothOppPreference( 1985): {}
D/BluetoothOppPreference( 1985): Dumping Channels:  
D/BluetoothOppPreference( 1985): {}
,D/OppService( 1985): Start()
W/BluetoothOPPServiceJni( 1985): initOppNative
D/BluetoothOPPServiceJni( 1985): initOppNative(L383): OPP
I/bluedroid( 1985): get_profile_interface opp
I/bt-btif ( 1985): btif_op_get_interface
D/BluetoothOPPServiceJni( 1985): initOppNative(L411): mOppCallbacksObj 2098426
D/BluetoothOPPServiceJni( 1985): initOppNative(L413): calling OPP init
D/WiFiOffLoadUpdatePriority( 5478): remove : truetruefalse
I/bt-btif ( 1985): btif_opp_init
D/bt-btif ( 1985): btif_enable_service: current services:0xa0632330
D/BluetoothOPPServiceJni( 1985): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 1985): initOppNative(L430): mOppCallbacksObj 2098426
V/OppService( 1985): setOppService(): set to: com.broadcom.bt.service.opp.OppService@224a8c24
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
V/OppService( 1985): pendingUpdate is :  true
D/HeadsetStateMachine( 1985): Proxy object connected
D/LGBluetoothHfpAdapter( 1985): [BTUI] queryPhoneState
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothA2dp( 1985): Proxy object connected
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
D/LGBluetoothPowerControlManager( 1985): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@1237ad53
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetPhoneState( 1985): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1985): Disconnected process message: 11, size: 0
V/OppService( 1985): Deleted complete outbound shares, number =  0
D/WiFiOffLoadUpdatePriority( 5478): remove2
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,V/OppService( 1985): Deleted complete inbound failed shares, number = 0
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
V/BluetoothOppProvider( 1985): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
V/WiFiOffLoadSharedPrefsUtils( 5478): save wifi state
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/WiFiOffLoadSharedPrefsUtils( 5478): save remove
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@19b64690 on behalf of 
D/WiFiOffLoadBroadcast( 5478): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/WiFiOffLoadBroadcast( 5478): S: false, R: true
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@1f7c1b89 on behalf of 
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 1985): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppNotification( 1985): update too frequent, put in queue
V/OppService( 1985): pendingUpdate is :  false
E/OppService( 1985): UpdateThread is Completed
,D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothPbapReceiver( 1985): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1985): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1985): ***********state = 11
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1985): Handler(): got msg=1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
,D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 1985): new notify threadi!
V/BluetoothOppNotification( 1985): send delay message
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() - All profile services started.
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/OppService( 1985): ContentObserver received notification
V/OppService( 1985): ContentObserver received notification
D/BluetoothAdapterState( 1985): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1985): enable
I/bt-btif ( 1985): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1985): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/OppService( 1985): pendingUpdate is :  true
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@d31a78e on behalf of 
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppNotification( 1985): mUpdateCompleteNotification = true
I/bt_hci_bdroid( 1985): init
I/bt_vendor( 1985): init
I/bt_vnd_conf( 1985): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,I/bt_vnd_conf( 1985): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/GKI_LINUX( 1985): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 1985): btu_task pending for preload complete event
I/bt-btif ( 1985): libbt-hci init returns 0
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@2505cbaf on behalf of 
V/OppService( 1985): pendingUpdate is :  false
E/OppService( 1985): UpdateThread is Completed
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@3fe13bbc on behalf of 
V/BluetoothOppNotification( 1985): outbound: succ-0  fail-0
,I/ActivityManager(  904): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5526 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/NotificationManager( 1985): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
,V/BluetoothOppNotification( 1985): outbound notification was removed.
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@281e745 on behalf of 
V/BluetoothOppNotification( 1985): inbound: succ-0  fail-0
I/NotificationManager( 1985): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1985): inbound notification was removed.
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@a24ae9a on behalf of 
,I/bt_userial_vendor( 1985): userial vendor open: opening /dev/ttyHS99
,D/bt_userial_vendor( 1985): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1985): device fd = 67 open
D/bt_hwcfg( 1985): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 1985): hw_config_cback state=1
,I/ActivityManager(  904): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5544 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  904): RTC_WAKEUP set : Alarm{376bb9ee type 0 when 1454063350643 com.android.vending} when 1454063350643
,D/bt_hwcfg( 1985): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 1985): hw_config_cback state=4
,D/bt_hwcfg( 1985): Chipset Name: BCM4334B0
D/bt_hwcfg( 1985): Chipset BCM4334B0
D/bt_hwcfg( 1985): Target name = [BCM4334B0]
I/bt_hwcfg( 1985): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1985): hw_config_cback state=2
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1985): hw_config_cback state=3
I/bt_hwcfg( 1985): bt vendor lib: set UART baud 4000000
D/BluetoothPermissionRequest( 5478): onReceive
,D/LGBluetoothFeatureConfig( 5478):  get() - isFeatureLoaded : false
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 1985): hw_config_cback state=5
,D/BluetoothManagerService(  904): Message: 20
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2180851c:true
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
V/BluetoothSapReceiver( 1985): [BTUI] checkServiceStart
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/LGBluetoothStateChangeReceiver( 1985): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/ActivityManager(  904): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5563 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/Tethering(  904): sendTetherStateChangedBroadcast 1, 0, 0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/DSQN    (  904): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/PCSuite ( 5526): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/ActivityManager(  904): Killing 5162:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
E/wpa_supplicant( 5472): USIM:  scard_init function
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/wpa_supplicant( 5472): rfkill: Cannot open RFKILL control device
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 9
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
W/libprocessgroup(  904): failed to open /acct/uid_10069/pid_5162/cgroup.procs: No such file or directory
I/wpa_supplicant( 5472): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/wpa_supplicant( 5472): wlan0: CTRL-EVENT-SCAN-STARTED 
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/WifiStateMachine(  904): MAC Addr from driver = a0:39:f7:70:12:80
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  904): setPowerSaveActivated(false)
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/ActivityManager(  904): Process com.google.android.talk (pid 4990) has died
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/WifiServerServiceExt(  904): WIFI_STATE_CHANGED_ACTION [3]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:11.052 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
E/WifiServerServiceExt(  904): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/WifiServerServiceExt(  904): batteryPsActivateMsgHandler : state:0 event:3
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/UsbSettingsReceiver( 5478): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5478): [AUTORUN] sys.usb.config = ptp_only,adb
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/UsbSettingsReceiver( 5478): [AUTORUN] sys.usb.state = ptp_only,adb
D/bt_hwcfg( 1985): hw_config_cback state=6
D/UsbSettingsReceiver( 5478): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/UsbSettingsReceiver( 5478): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
W/ResourcesManager( 5563): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/WifiConfigStore(  904): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/WifiStateMachine(  904): enableVerboseLogging : level 2
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/WifiStateMachine(  904): Setting OUI to DA-A1-19
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/WfdsService( 1806): Supplicant Connection state is changed : true
D/WifiNative-HAL(  904): Setting external_sim to 1
D/WfdsService( 1806): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1806): Set the WFDS Monitor: true
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/WifiNative-HAL(  904): startHal
E/wifi    (  904): getStaticLongField sWifiHalHandle 0x9abc88ec
I/WifiHAL (  904): Initializing wifi
I/WifiHAL (  904): Creating socket
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/WfdsMonitor( 1806): WfdsMonitorThread create
D/WfdsMonitor( 1806): WFDS Monitor is created and started
D/WfdsService( 1806): WiFi: Supplicant connection re-established
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/WifiHAL (  904): Initialized Wifi HAL Successfully; vendor cmd = 103
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/wifi    (  904): Did set static halHandle = 0xaafe7e40
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
E/CtrlSupplicant( 1806): Access OK "@android:wpa_wlan0"
D/wifi    (  904): halHandle = 0xaafe7e40, mVM = 0xb487c280, mCls = 0x50113a
E/wifi    (  904): getStaticLongField sWifiHalHandle 0x9abc889c
,D/wifi    (  904): array field set
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/WifiNative-HAL(  904): interface[0] = wlan0
I/WifiNative-HAL(  904): interface[1] = p2p0
E/CtrlSupplicant( 1806): Succeed to open control connection
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/wifi    (  904): setting scan oui 0x9ccabc70
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
E/CtrlSupplicant( 1806): Succeed to open monitor connection
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/WfdsMonitor( 1806): Supplicant connection established
D/bt_hwcfg( 1985): hw_config_cback state=6
D/WfdsService( 1806): Connected to the supplicant for wfds
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/WifiHAL (  904): Sending mac address OUI
E/WifiHAL (  904): failed to set scanning mac OUI; result = -95
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/WifiStateMachine(  904): Setting OUI to DA-A1-19
I/WifiNative-HAL(  904): startHal
D/wifi    (  904): setting scan oui 0x9ccabc70
D/WifiHAL (  904): Sending mac address OUI
E/WifiHAL (  904): failed to set scanning mac OUI; result = -95
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 1985): hw_config_cback state=6
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  904): hidePasspointNotification off =false
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:11.12 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiNative-HAL(  904): Waiting for HAL events mWifiHalHandle=-1426162112
D/wifi    (  904): waitForHalEvents called, vm = 0xb487c280, obj = 0x50113a, env = 0x9cce32e0
E/wifi    (  904): getStaticLongField sWifiHalHandle 0x96fd4b2c
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,D/LGWifiP2pService(  904): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  904): SCAN_AVAILABLE : 3
D/RttService(  904): SCAN_AVAILABLE : 3
D/WifiScanningService(  904): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  904): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  904): startHal
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/wifi    (  904): getting scan capabilities on interface[0] = 0x9ccabc70
,D/WifiHAL (  904): Creating message to get scan capablities; iface = 24
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/wifi    (  904): failed to get capabilities : -95
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/WifiScanningService(  904): could not get scan capabilities
D/CommandListener(  281): Setting iface cfg
D/CommandListener(  281): Trying to bring up p2p0
,D/WifiMonitor(  904): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService(  904): P2pEnablingState
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/LGWifiP2pService(  904): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  904): P2p socket connection successful
D/LGWifiP2pService(  904): P2pEnabledState
I/WifiServerServiceExt(  904): set CMD_ADD_DEFAULT_PROFILE
D/LGWifiP2pService(  904): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  904): before postfix = G3s-1
D/WifiServerServiceExt(  904): postfix byte check : 5
D/LGWifiP2pService(  904): after postfix = G3s-1
I/WifiServerServiceExt(  904): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 5472): nWIFIDualbandAPConnection: 1
I/WifiServerServiceExt(  904): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 5472): disconnect_rssi_lvl: -100
I/WifiServerServiceExt(  904): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
E/wpa_supplicant( 5472): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
I/WifiServerServiceExt(  904): set CMD_UPDATE_DEFAULT_PROFILE
,D/LGBluetoothProfileConnectionReceiver_EasySetting( 5563): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
,D/Finsky  ( 5544): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/AuthorizationBluetoothService( 1733): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/UsbSettingsControl( 5478): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 5478): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5478): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5478): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5478): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5478): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 5478): [AUTORUN] setTetherStatus() : status=false
,I/wpa_supplicant( 5472): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
I/wpa_supplicant( 5472): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WiFiOffLoadUpdatePriority( 5478): remove : truetruetrue
,I/bt_hwcfg( 1985): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 1985): Settlement delay -- 100 ms
I/bt_hwcfg( 1985): Setting fw settlement delay to 100 
,D/WifiNative-HAL(  904): p2pGetDeviceAddress
D/WifiNative-HAL(  904): p2pGetDeviceAddress returning a2:39:f7:70:12:80
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:11.225 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WfdsService( 1806): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/LGWifiP2pService(  904): DeviceAddress: a2:39:f7:70:12:80
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
D/WfdsService( 1806): Update P2p Interface State: 3
,I/wpa_supplicant( 5472): wlan0: Associated with c0:ff:d4:d3:aa:48
D/LGWifiP2pService(  904): sending p2p persistent groups changed broadcast
D/LGWifiP2pService(  904): sending p2p connection changed broadcast
D/LGWifiP2pService(  904): InactiveState
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1806): WifiP2pState is changed : true
D/WfdsService( 1806): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsService( 1806): Receive the WFDS_ENABLE Method
D/WfdsService( 1806): Set the WFDS Monitor: true
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1806): Connected to the supplicant for wfds
D/WfdsJNI ( 1806): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 5472): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1806): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 5472): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1806): doCommand: WFDS_CLEAR_PD_INFO
I/wpa_supplicant( 5472): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WfdsJNI ( 1806): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsJNI ( 1806): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1806): selectPreferredScanChannel [6]
D/WfdsService( 1806): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
D/WfdsService( 1806): isConnected: false
D/LGWifiP2pService(  904): InactiveState{ when=-9ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-9ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): DefaultState{ when=-9ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LocSvc_java(  904): onReceive
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt(  904): No p2p device connected
D/WfdsService( 1806): GroupInfoAvailable: mGroupInfo is null
D/LGWifiP2pService(  904): InactiveState{ when=-2ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): DefaultState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1806): DefaultState - msg [9441285] is not handled
,W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:11.283 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:11.286 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  904): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  904): setSupplicantStateSCANNING
D/GONS    ( 1743): GONS isTestMode: false Country: 
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:11.301 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:11.307 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/wpa_supplicant( 5472): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5472): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  904): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  904): setSupplicantStateASSOCIATING
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1985): hw_config_cback state=2
D/WifiServerServiceExt(  904): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  904): setSupplicantStateASSOCIATED
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1985): hw_config_cback state=7
I/bt_hwcfg( 1985): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 1985): Setting local bd addr to F8:95:C7:87:85:54
D/WiFiOffLoadUpdatePriority( 5478): remove1
V/WiFiOffLoadSharedPrefsUtils( 5478): save remove
,I/WifiServiceExtension(  904): setVHTCapabilityType  : false
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 1985): hw_config_cback state=8
I/bt_hwcfg( 1985): vendor lib fwcfg completed
I/bt-btif ( 1985): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 1985): btu_task received preload complete event
,D/WiFiOffLoadBroadcast( 5478): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5478): S: false, R: false
D/Finsky  ( 5544): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/WifiServerServiceExt(  904): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  904): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  904): setSecurityType  : 2
I/        ( 1985): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 1985): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 1985): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 1985): BTE_InitTraceLevels -- TRC_PROTOCOL,0
W/Settings( 5544): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5544): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 5544): com.android.vending: cancel(-1050172287) by com.android.vending
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:11.412 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:11.414 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,D/ConnectivityService(  904): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  904): Got NetworkAgent Messenger
D/ConnectivityService(  904): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  904): NetworkAgent connected
D/WifiExtManager(  904): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@28cc2977
D/WifiExtManager(  904): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@1c9a19e4
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
E/WifiConfigStore(  904): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/AlarmManager(  904): ELAPSED_WAKEUP set : Alarm{a0ee249 type 2 when 87858 com.android.providers.calendar} when 87858
,E/WifiConfigStore(  904): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/DownloadManager( 3135): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@3ecb14a9 on behalf of 5544
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  281): Setting iface cfg
D/Finsky  ( 5544): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5544): [1] Libraries$2.run: Finished loading 1 libraries.
D/DhcpStateMachine(  904): StoppedState
E/WifiStateMachine(  904): Start Dhcp Watchdog 1
D/DhcpStateMachine(  904): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  904): WaitBeforeStartState
,D/WifiServerServiceExt(  904): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  904): setSupplicantStateFOUR_WAY_HANDSHAKE
D/Finsky  ( 5544): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/WifiServerServiceExt(  904): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  904): setSupplicantStateGROUP_HANDSHAKE
D/Ads     ( 5544): Skipping gmscore version check
D/WiFiOffLoadUpdatePriority( 5478): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5478): connected SSID: null
D/WiFiOffLoadUpdatePriority( 5478): private wpa: "NG700" 300
I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-63 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:11.493 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/WifiServiceImplEx(  904): addOrUpdateNetwork pid=5478, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork(  904):  uid = 1000 SSID "NG700" nid=0
D/ConnectivityService(  904): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/Finsky  ( 5544): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/bt-btif ( 1985): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,I/GKI_LINUX( 1985): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 1985): warning : media task started media_task_refcnt 1 
D/BT_PROF_AUDIO( 1985): created moving average (N=100)
D/BT_PROF_AUDIO( 1985): reset rate average
W/bt-btif ( 1985): overflow 0, enter 0, exit 0
E/bt-btif ( 1985): Calling BTA_HhEnable
E/bt-btif ( 1985): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 1985): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1985): Address is:F8:95:C7:87:85:54
W/bt-smp  ( 1985): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1985): Plain text(LSB ~ MSB) = 3c 04 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1985): Encrypted text(LSB ~ MSB) = 8a 66 d4 ed aa d1 df 91 d8 7f c7 af 32 85 48 f4 
W/bt-btm  ( 1985): Stopping oneshot timer
D/BluetoothManagerService(  904): Bluetooth Adapter name changed to G3s-1
D/BluetoothAdapterProperties( 1985): Name is: G3s-1
D/BluetoothManagerService(  904): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 1985): Scan Mode:20
D/BluetoothAdapterProperties( 1985): Discoverable Timeout:120
E/bt-btif ( 1985): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 1985): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 1985): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 1985): BTA_JvEnable
E/bt-btif ( 1985): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 1985): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 1985): init_hci_slots(L136): in
D/IOP_DB_BT( 1985): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 1985): db_open: db_open : handle 2690893788l, read 11046 bytes onto local cache
D/IOP_DB_BT( 1985): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1985): db_query: result 1
I/        ( 1985): iop_db_open: iop_db_open status 0
E/bt-btif ( 1985): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 1985): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 1985): bta_pan_co_init
D/bte_conf( 1985): Device ID record 1 : primary
D/bte_conf( 1985):   vendorId            = 00c4
D/bte_conf( 1985):   vendorIdSource      = 0001
D/bte_conf( 1985):   product             = 13a1
D/bte_conf( 1985):   version             = 1000
D/bte_conf( 1985):   clientExecutableURL = 
D/bte_conf( 1985):   serviceDescription  = 
D/bte_conf( 1985):   documentationURL    = 
D/bte_conf( 1985): bte_load_did_conf no section named DID2.
I/bt-btif ( 1985): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 1985): btif_hf_upstreams_evt: wrong handle = 8240 
I/bt-btif ( 1985): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 1985): opc_state_cb(L140):  opc_state_cb state:0
D/BluetoothAdapterState( 1985): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1985): ScanMode =  20
D/BluetoothAdapterProperties( 1985): State =  11
D/BluetoothAdapterProperties( 1985): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 1985): Setting state to 12
I/BluetoothAdapterState( 1985): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(164330702)( 1985): updateAdapterState() - Broadcasting state to 1 receivers.
D/OppService( 1985): onOpcStateChange()
I/bt-btif ( 1985): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1985): ops_state_cb(L223):  ops_state_cb state:0
D/OppService( 1985): Recieved MESSAGE_OPC_ENABLE
D/OppService( 1985): onOpsStateChange() :0
I/bt-btif ( 1985): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1985): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1985): onFtpServerEnabled: /storage
D/BluetoothManagerService(  904): Message: 60
D/BluetoothManagerService(  904): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothPanServiceJni( 1985): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/bt-btif ( 1985): HAL bt_hal_cbacks->adapter_properties_cb
D/LGBluetoothFeatureConfig( 1985): isPrivacyLogsEnabled : true
D/BluetoothManagerService(  904): Broadcasting onBluetoothStateChange(true) to 6 receivers.
I/BluetoothAdapterState( 1985): Entering On State
I/BluetoothAdapterState( 1985): Entering On State from state = 11
D/BluetoothA2dp( 1985): onBluetoothStateChange: up=true
D/BluetoothA2dp(  904): onBluetoothStateChange: up=true
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterProperties( 1985): Scan Mode:21
D/BluetoothAdapterService(164330702)( 1985): isQuetModeEnabled() - Enabled = false
I/bt-btif ( 1985): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1985): Discoverable Timeout:120
D/BluetoothAdapterService(164330702)( 1985): autoConnect() - Initiate auto connection on BT on...
D/BluetoothHeadset( 1743): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 1985): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset(  904): onBluetoothStateChange: up=true
D/OppService( 1985): Recieved MESSAGE_OPS_ENABLE
D/BluetoothHeadset( 1743): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1743): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 1985): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1985): [BTUI]         global_name: G3s-1
,D/LGBluetoothServiceAdapter( 1985): [BTUI]         local_name: G3s-1
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
E/BluetoothManagerService(  904): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothAdapterService(164330702)( 1985): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(164330702)( 1985): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1985): [BTUI] autoConnect() : not allowed
D/BluetoothManagerService(  904): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothAPIService( 1806): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothManagerService(  904): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  904): Message: 40
D/BluetoothManagerService(  904): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/LGBluetoothAPIService( 1806): Message: 1
D/LGBluetoothAPIService( 1806): MESSAGE_BOOT_COMPLETED
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1373): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
I/BluetoothMapService( 1985): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothMapService( 1985): STATE_ON
D/bt_h4   ( 1985): vendor lib postload completed
I/LGBluetoothAPIService( 1806): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
,V/BluetoothPbapService( 1985): Pbap Service onCreate
V/BluetoothPbapService( 1985): Starting PBAP service
D/LGWifiP2pService(  904): InactiveState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d7adcf1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d7adcf1 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  904): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  904): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  904): Current State is mWaitBeforeStartState.
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/LGBluetoothPbapAdapter( 1985): [BTUI] getInstance : create
D/DhcpStateMachine(  904): DHCP Start wake lock is acquired.
V/BluetoothPbapService( 1985): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1985): state: 12
V/BluetoothMapService( 1985): Handler(): got msg=1
D/BluetoothMapMasInstance( 1985): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 1985): MAS initSocket()
V/LgDhcpStateMachineHelper(  904): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  904): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/BluetoothMapMasInstance( 1985):   masId = 00
D/BluetoothMapMasInstance( 1985):   msgTypes = 0e
D/BluetoothMapMasInstance( 1985):   masName = SMS/MMS
D/BluetoothMapMasInstance( 1985):   SDP string = 000eSMS/MMS
D/LGBluetoothAPIServer( 1985): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1985): [BTUI] onBind()
,D/WifiServerServiceExt(  904): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  904): setSupplicantStateCOMPLETED
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppNotification( 1985): new notify threadi!
V/BluetoothOppNotification( 1985): send delay message
V/BluetoothPbapService( 1985): Handler(): got msg=1
V/BluetoothPbapService( 1985): Pbap Service startRfcommSocketListener
W/BluetoothAdapter( 1985): getBluetoothService() called with no BluetoothManagerCallback
D/WifiServerServiceExt(  904): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  904): setSupplicantStateCOMPLETED
D/LGBluetoothAPIService( 1806): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1806): Message: 100
D/LGBluetoothAPIService( 1806): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1985): [BTUI] createSocketChannel FD=83 mFd=0
V/BluetoothMapMasInstance( 1985): Succeed to create listening socket 
D/BluetoothMapMasInstance( 1985): Accepting socket connection...
V/BluetoothPbapService( 1985): Pbap Service initSocket
E/WifiConfigStore(  904):  key="NG700"WPA_PSK netId=0 uid=0/1000
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@45eb2c1 on behalf of 
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 1985): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 1985): mUpdateCompleteNotification = true
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1985): [BTUI] createSocketChannel FD=86 mFd=83
V/BluetoothPbapService( 1985): Succeed to create listening socket 
V/BluetoothPbapService( 1985): Accepting socket connection...
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@390f1a66 on behalf of 
V/BluetoothOppNotification( 1985): outbound: succ-0  fail-0
I/NotificationManager( 1985): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1985): outbound notification was removed.
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@365d81a7 on behalf of 
V/BluetoothOppNotification( 1985): inbound: succ-0  fail-0
I/NotificationManager( 1985): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1985): inbound notification was removed.
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@117b4654 on behalf of 
,E/WifiConfigStore(  904): Setting BSSID for "NG700"WPA_PSK to any
,D/WiFiOffLoadUpdatePriority( 5478):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5478): configuration updated: 0
,I/WifiServerServiceExt(  904): set CMD_UPDATE_DEFAULT_PROFILE
D/WiFiOffLoadUpdatePriority( 5478): configuration saved: true
,D/PCSuite ( 5526): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ContextImpl( 5478): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,D/Finsky  ( 5544): [660] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5544): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  904): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5625 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
V/BluetoothPbapReceiver( 1985): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1985): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1985): ***********state = 12
,D/DhcpStateMachine(  904): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  904): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  904): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 5634): version 5.5.6 starting
,E/dhcpcd  ( 5634): get_duid: Read-only file system
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/LocalBluetoothProfileManager( 5478): Adding local A2DP profile
D/BluetoothManagerService(  904): Message: 30
D/LocalBluetoothProfileManager( 5478): Adding local HEADSET profile
,D/BluetoothManagerService(  904): Message: 30
D/BluetoothManagerService(  904): Message: 30
,D/BluetoothManagerService(  904): Message: 30
D/LocalBluetoothProfileManager( 5478): Adding local MAP profile
D/BluetoothMap( 5478): Create BluetoothMap proxy object
D/BluetoothManagerService(  904): Message: 30
,D/BluetoothManagerService(  904): Message: 30
D/LocalBluetoothProfileManager( 5478): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 1985): Pbap Service onBind
,D/LGBluetoothUserBindClient( 5478): [BTUI] initUserBindClient
W/ContextImpl( 5478): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,I/dhcpcd  ( 5634): wlan0: rebinding lease of 192.168.1.134
D/DockEventReceiver( 5478): finishStartingService: stopping service
D/BluetoothA2dp( 5478): Proxy object connected
D/A2dpProfile( 5478): Bluetooth service connected
,D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothHeadset( 5478): Proxy object connected
D/HeadsetProfile( 5478): Bluetooth service connected
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothInputDevice( 5478): Proxy object connected
D/HidProfile( 5478): Bluetooth service connected
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothPan( 5478): BluetoothPAN Proxy object connected
D/PanProfile( 5478): Bluetooth service connected
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothMap( 5478): Proxy object connected
,D/MapProfile( 5478): Bluetooth service connected
D/BluetoothMap( 5478): getConnectedDevices()
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
V/BluetoothMapService( 1985): getConnectedDevices()
D/BluetoothPbap( 5478): Proxy object connected
D/PbapServerProfile( 5478): Bluetooth service connected
D/LGBluetoothUserBindClient( 5478): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 5478): onReceive
D/LGBluetoothFeatureConfig( 5478): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 5478): [BTUI] FileNotFound: readProperty
I/ActivityManager(  904): Killing 4762:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  904): failed to open /acct/uid_10086/pid_4762/cgroup.procs: No such file or directory
V/BluetoothOppReceiver( 1985): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,D/LGDMClient( 5625): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5625): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/BluetoothOppManager( 1985): restoreApplicationData! falsefalsenullnull
W/ContextImpl( 5625): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 5625): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,V/BluetoothSapReceiver( 1985): [BTUI] checkServiceStart
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGBluetoothStateChangeReceiver( 1985): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGDMClient( 5625): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/AuthorizationBluetoothService( 1733): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/LGDMClient( 5625): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/WiFiOffLoadBroadcast( 5478): MCCMNC not supported: null
D/LGDMClient( 5625): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/PCSuite ( 5526): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5526): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5526): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5478): MCCMNC not supported: null
,I/ActivityManager(  904): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5662 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  904): Killing 5233:com.google.android.gm/u0a53 (adj 15): empty #11
I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 6
,D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/libprocessgroup(  904): failed to open /acct/uid_10053/pid_5233/cgroup.procs: No such file or directory
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,V/[BNRBootReceiver]( 5662): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5662): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5662): Boot Receiver Return
,W/MainApplication( 5662): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 5478): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5478): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5478): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5478): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5478): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5478): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5478): MCCMNC not supported: null
D/CalendarProviderBroadcastReceiver( 5390): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5390): [IntentService] WakeLock acquire, start IntentSerivce
,D/CalendarProvider2( 5390): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 5390): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5390): [getOrCreateCalendarAlarmManager]
,I/art     (  904): Explicit concurrent mark sweep GC freed 53774(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.354ms total 157.655ms
,D/CalendarProvider2( 5390): [IntentService] Release Lock
,D/CalendarProvider2( 5390): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  904): Killing 4819:com.google.process.gapps/u0a6 (adj 15): empty #11
W/libprocessgroup(  904): failed to open /acct/uid_10006/pid_4819/cgroup.procs: No such file or directory
,D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  904): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/AlertService( 5425): Beginning updateAlertNotification
,D/AlertService( 5425): No fired or scheduled alerts
I/NotificationManager( 5425): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(10) by com.android.calendar
,I/NotificationManager( 5425): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5425): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5425): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,V/AudioFlinger(  286): thread 0xb5651000 type 0 TID 1291 going to sleep
V/AudioFlinger(  286): thread 0xb5735000 type 0 TID 1297 going to sleep
V/AudioFlinger(  286): thread 0xb56eb000 type 0 TID 1295 going to sleep
,D/AlarmScheduler( 5425): No events found starting within 1 week.
I/dhcpcd  ( 5634): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5634): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  904): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/ActivityManager(  904): Killing 5425:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  904): failed to open /acct/uid_10013/pid_5425/cgroup.procs: No such file or directory
,D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  904): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  904): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  904): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  904): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  904): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  904): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  904): bShouldSendDhcpAction Result: true
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  904): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  904): RunningState
E/WifiStateMachine(  904): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService(  904): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/ConnectivityService(  904): ignoring duplicate network state non-change
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  904): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  904): Adding iface wlan0 to network 100
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-63 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:13.642 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-63 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:13.646 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-63 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:13.649 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiHS20(  904): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-63 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:13.657 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/WifiHS20(  904): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine(  904): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
D/WiFiOffLoadBroadcast( 5478): MCCMNC not supported: null
E/ConnectivityService(  904): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  904): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  904): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  904): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  904): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  904): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  904): Setting Dns servers for network 100 to [/192.168.1.1]
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/Nat464Xlat(  904): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  904): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  904): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  904): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  904):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  904):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  904):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  904): currentScore = 0, newScore = 20
D/ConnectivityService(  904):    accepting network in place of null
D/ConnectivityService(  904): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  904): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  904):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  904): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/TelephonyNetworkFactory-1( 1743): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
,D/TelephonyNetworkFactory-1( 1743):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): [LWD] Start DNSResolver start to wait
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): [LWD] wait 500ms before dns check
E/ConnectivityService(  904): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  904): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/CSLegacyTypeTracker(  904): [e] list.add(nai) empty : false size: 1
W/QCNEJ   ( 1842): |CORE| No family connected
I/QCNEJ   ( 1842): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  904): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  904): MasterInitialState.processMessage what=3
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=0
D/ConnectivityService(  904): validation of new default Network = false
D/ConnectivityService(  904): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  904): enableDataServiceNotify 
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/DSQN    (  904): start dsqn bin
I/QCNEJ   ( 1842): |CORE| sendDefaultNwMsg: default = 1
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/DSQN    (  904): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/NetworkPolicy(  904): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 5478): MCCMNC not supported: null
D/ConnectivityService(  904): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
I/DSQN    ( 5730): DSQN samuel.seo ver 141203
E/DSQN    ( 5730): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5730): created command queue thread
I/DSQN    ( 5730): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5730): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/WiFiOffLoadBroadcast( 5478): MCCMNC not supported: null
I/PCSuite ( 5526): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5526): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 5478): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5478): MCCMNC not supported: null
I/PCSuite ( 5526): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5526): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): [LWD] DNSResolver start dns
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out(  904): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:29:14.51 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/DSQN    ( 5730): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 5730): restart monitoring
I/DSQN    ( 5730): dsqn report finish
D/LGDataListener(  281): argv[0]=dsqncommand
D/LGDataListener(  281): argv[1]=wlan0
D/LGDataListener(  281): argv[2]=1
D/LGDataListener(  281): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  904): DSQM DsqnNotification wlan0  1
D/DSQN    (  904): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 10:29:13 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454063354740], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454063354690]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): Validated
D/ConnectivityService(  904): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  904): rematching NetworkAgentInfo [WIFI () - 100]
D/WifiDataContinuityService(  904): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  904):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  904):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  904): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  904): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/WifiServerServiceExt(  904): set CMD_CAPTIVE_CHECK_COMPLETED
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/ConnectivityService(  904): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  904): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1743): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  904):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1743):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/AlarmManager(  904): RTC_WAKEUP set : Alarm{2bb3720e type 0 when 1454063355105 com.android.vending} when 1454063355105
,D/Finsky  ( 5544): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  904): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5750 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 304us total 37.181ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.634ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.080ms
,I/GservicesProvider( 5750): Gservices pushing to system: true; secure/global: true
,I/NotificationManager( 1936): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
I/GoogleHttpClient( 5750): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5750): GMS http client unavailable, use old client
,I/NotificationManager(  904): android: cancelAsUser(2) by android
,D/libc-netbsd( 5544): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5544): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5544): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5544): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out( 5544): propertyValue:false
D/libc-netbsd( 5544): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5544): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/WifiInternetCheck(  904): Single check msg out of sync, ignoring.
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/LocSvc_java(  904): onReceive
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  904): got connectivity action
D/GpsLocationProvider(  904): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  904): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  904): Sending msg: 4 arg1:1 arg2:1
,D/LocSvc_java(  904): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  904): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  904): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  904): Sending msg: 5 arg1:0 arg2:1
I/ActivityManager(  904): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5794 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out(  904): propertyValue:false
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out(  904): propertyValue:false
I/System.out(  904): propertyValue:false
,D/NetworkChangeNotifierAutoDetect( 1936): Network connectivity changed, type is: 2
,I/ActivityManager(  904): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5827 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5827): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5827): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5827): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/GpsLocationProvider(  904): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/GpsLocationProvider(  904): No APN found to select.
,D/LgeGpsConstants(  904): Can't find 'ext_gps.conf'!!
,E/ActivityThread( 4023): Failed to find provider info for com.android.contacts.metadata
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  904): NTP server returned: 1454063356009 (Fri Jan 29 11:29:16 GMT+01:00 2016) reference: 93566 certainty: 164 system time offset: -1152
D/AlarmManagerService(  904): Setting time of day to sec=1454063356
W/AlarmManagerService(  904): Unable to set rtc to 1454063356: Invalid argument
D/LocSvc_java(  904): Sending msg: 10 arg1:0 arg2:1
,I/ActivityManager(  904): Process com.lge.lgdmsclient (pid 5625) has died
D/SyncManager(  904): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 37693, reason: UserStart, SyncResult: databaseError: true stats []
,I/[SystemUI]Clock( 1373): onReceive = android.intent.action.TIME_SET
,D/SyncManager(  904): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 123806, reason: UserStart
I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
I/CalendarProvider2( 5390): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 5390): Scheduling check of next Alarm
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out(  904): propertyValue:false
I/NotificationManager(  904): android: cancelAsUser(716319171) by android
D/WeatherService( 2763): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:29:16
D/WeatherService( 2763): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2763): 2 : This is isUpdating : false
D/WeatherService( 2763): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2763): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2763): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2763): 2 : Fixed theme : optimus
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/WeatherReflect( 2763): 2 : Map key string is -2
,I/ActivityManager(  904): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5855 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ActivityManager(  904): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 1880): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=29 currentDate=-1 dayofweek=6 currentDayOfWeek=-1
,D/LgeGpsLocationProvider(  904): NTP server: europe.pool.ntp.org
D/LgeGpsLocationProvider(  904): NTP server returned: 1454063356284 (Fri Jan 29 11:29:16 GMT+01:00 2016) reference: 93704 certainty: 37 system time offset: 142
I/NotificationManager(  904): android: cancelAsUser(-1816247584) by android
D/lim     ( 2763): 2 : time = 11:29
I/WeatherReflect( 2763): Model Name : LG-D722
D/WeatherTheme( 2763): 2 : exactly same view!
D/WeatherTheme( 2763): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2763): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:29:16
,I/[LGHome]LGCalendarIcon( 1880): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 29
I/[LGHome]LGCalendarIcon( 1880): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 29
I/AppConfig( 5827): Total System Memory = 906309632
,I/GalleryUtils( 5827): Application Heap = 96 MB
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/AppConfig( 5827): App Tier : NOT_DEF
,D/SystemHelper( 5827): region [EU], country [EU], operator [OPEN], sub-operator []
,I/NotificationManager(  904): android: cancelAsUser(-1597574061) by android
W/ResourcesManager( 5855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5855): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5855): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/MusicStore( 5794): Database version: 120
,E/Auth.Api.Credentials( 4023): [CredentialSyncAdapter] Unknown sync event.
,D/libc-netbsd( 5544): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5544): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  904): Process com.lge.bnr (pid 5662) has died
,I/NotificationManager(  904): android: cancelAsUser(-591465577) by android
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5794): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/NotificationManager(  904): android: cancelAsUser(-1816247584) by android
,I/LGEmail ( 5855): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/NotificationManager(  904): android: cancelAsUser(-1597574061) by android
,E/ConnectivityChangeReceiver( 4023): Ignoring connectivity change
,D/LGEmail ( 5855): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/ConnectivityService(  904): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  904): dumpNetworkRequest
D/ConnectivityService(  904):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  904):     Requests:
D/ConnectivityService(  904):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904):     Lingered:
D/ConnectivityService(  904): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  904): apparently satisfied.  currentScore=60
D/ConnectivityService(  904): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 4023): CM callback handler got msg 524290
I/ActivityManager(  904): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=5888 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5794): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5794): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/sensors_hal_Time(  904): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  904): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  904): tsOffsetIs: Apps: 94302878562; DSPS: 3188850; Offset : -3017702289
I/NotificationManager(  904): android: cancelAsUser(-591465577) by android
,W/ResourcesManager( 5888): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5794): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5794): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out(  904): propertyValue:false
,D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out(  904): propertyValue:false
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  904): android: cancelAsUser(2) by android
,I/ActivityManager(  904): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=5917 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,V/JNIHelp ( 5794): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/jxcore-log( 5327): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5327): 
,I/qtaguid ( 5544): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5544): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5544): untagSocket(41) failed with errno -22
V/WifiInternetCheck(  904): isHttpConnectionAvailable - We got a valid response : 204
I/ActivityManager(  904): Process com.lge.settings.easy (pid 5563) has died
,D/Finsky  ( 5544): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,W/ActivityThread( 5794): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5794): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3946fe9f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5794): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5794): GMSCore installation verified
W/DriveInitializer( 4023): Awaiting to be initialized
W/DriveInitializer( 4023): Background init thread started
,I/ConfigStore( 5794): Config Database version: 1
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4023): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
D/ALBootInit( 5917): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 5917): Alarm ALBootInit: TIME_SET
D/Alarms  ( 5917): [setNextAlert] start
,D/Alarms  ( 5917): [setNextAlert] (1)
,D/Alarms  ( 5917):  minTime  = 0
D/Alarms  ( 5917):  -- OK multi -- 0
E/jeny.kim( 5917): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 5917): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/ActivityManager(  904): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5949 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  904): Explicit concurrent mark sweep GC freed 54352(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/34MB, paused 4.170ms total 251.770ms
,I/CommonUtil( 5917): BUILD Operator: OPEN
,D/Alarms  ( 5917): broadcastToWidgetProvider : false
D/Alarms  ( 5917): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,V/SettingsProvider(  904): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 5917): onReceive: android.intent.action.TIME_SET
W/DriveInitializer( 4023): Background init thread ended
V/DigitalAppWidgetProvider( 5917): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@383a49d0
,V/DigitalAppWidgetProvider( 5917): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@383a49d0
,W/ResourcesManager( 5949): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5949): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 28386(1911KB) AllocSpace objects, 28(448KB) LOS objects, 39% free, 13MB/22MB, paused 1.621ms total 260.044ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  904): Process com.android.settings (pid 5478) has died
,I/MultiDex( 5949): VM with version 2.1.0 has multidex support
I/MultiDex( 5949): install
I/MultiDex( 5949): VM has multidex support, MultiDex support library is disabled.
D/QuickCoverProvider( 5917): onReceiver
,I/NotificationManager(  904): android: cancelAsUser(2) by android
,I/ActivityManager(  904): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=5979 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5750): Explicit concurrent mark sweep GC freed 7874(398KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 502us total 48.587ms
,W/art     ( 5888): Attempt to remove local handle scope entry from IRT, ignoring
V/JNIHelp ( 5949): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 5979): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ActivityThread( 5949): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5949): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@bc1bdf4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5949): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  904): Process com.android.providers.calendar (pid 5390) has died
,D/CalendarApplication( 5979): CalendarApplication.onCreate()
I/NotificationManager( 5949): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5949): com.google.android.gms: cancel(39789) by com.google.android.gms
,I/NotificationManager(  904): android: cancelAsUser(353845882) by android
D/libc-netbsd( 5888): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5888): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  281): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  281): App 10086 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/PreferenceKeysParser( 5979): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 5979): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@35ef00f7, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3f18db64, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3c611cd, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@6503a82, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2488b593, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@383a49d0, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1a2efdc9, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@9cb7cce, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@ff17ef, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@17c232fc, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3420ad85, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@20a697da, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@35cf440b, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3b7d82e8, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@39c39d01, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@21e657a6, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@e2c15e7, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@f1be594, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@134c083d, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3e104832, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2b9a2983, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@279bc700, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3df5eb39, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3676b57e, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@394bdadf, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2976532c, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@34c101f5, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3d44ab8a, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@393d45fb, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@258b7618, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@28ecc871, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@a49f656, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@71046d7, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@18cddbc4, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@6347aad, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@308721e2, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2ca87973, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3aaef030, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3ecb14a9, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@797a2e, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@248739cf, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@64adf5c, l
I/Activity,Manager(  904): Process com.lge.sync (pid 5526) has died
D/GeneralPreferenceUtils( 5979): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
I/PhoneApp( 1743): onTrimMemory: 10
I/PhoneApp( 1743): trim memory
D/UEI.SmartControl( 5057): Service.onTrimMemory: 60
I/BackgroundMemoryTrimmer( 1936): Trimming objects from memory, since app is in the background.
D/Config  ( 5979): [init]
E/UEI.SmartControl( 5057): Setup service releasing memory...
,I/Config  ( 5979): LGCalendar ver.4.40.17
I/Config  ( 5979): start check model
I/Config  ( 5979): start check native_ca
I/Config  ( 5979): Config Operator=OPEN, Country=EU
D/Config  ( 5979): [setDefaultValuesToPref]
I/NotificationManager(  904): android: cancelAsUser(-1548111331) by android
D/Config  ( 5979): [parseProfiles]
D/ProfilesParser( 5979): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5979): [debug_displayParseInfos] profile.operator = null
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
D/Config  ( 5979): [updateProfiletoCountryInfo]
D/GeneralPreference( 5979): [checkAndMigrateOldPreference]
,I/qtaguid ( 5544): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5544): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5544): untagSocket(41) failed with errno -22
E/AgendaWidgetManager( 5979): [updateWidgets] 
I/InitNotificationRingtoneService( 5979): Start InitializeAlertRingtoneService.onHandleIntent
,I/art     ( 5057): Explicit concurrent mark sweep GC freed 153(17KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 352us total 65.351ms
,I/AlertUtils( 5979): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
D/ChimeraCfgMgr( 5949): Reading stored module config
I/AlertUtils( 5979): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
D/ChimeraCfgMgr( 5949): Loading module com.google.android.gms.car from APK com.google.android.gms
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5979): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/AlertUtils( 5979): set default noti to content://media/internal/audio/media/38
I/NotificationManager(  904): android: cancelAsUser(353845882) by android
,I/InitNotificationRingtoneService( 5979): End InitializeAlertRingtoneService.onHandleIntent
I/MediaRouter( 5794): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/ActivityManager(  904): Process com.lge.qremote (pid 5034) has died
,D/UEI.SmartControl( 5057): Service.onUnbind: IControl
I/BackgroundMemoryTrimmer( 1936): Trimming objects from memory, since app is in the background.
D/UEI.SmartControl( 5057): Service.onDestroy
I/art     ( 5888): CheckpointMarkThreadRoots callback created = 0xb0543530
I/PhoneApp( 1743): onTrimMemory: 10
I/PhoneApp( 1743): trim memory
,V/MusicLeanback( 5794): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/UEI.SmartControl( 5057): Shutdown IRRCPlayer... 
,W/irrc_jni( 5057): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5057): ~IrrcClient ++ 
D/irrcClient( 5057): ~IrrcClient -- 
W/irrc_jni( 5057): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5057): Blaster closed
D/UEI.SmartControl( 5057): Blaster closed
D/UEI.SmartControl( 5057): Shut down QS...
D/UEI.SmartControl( 5057): Stopped file observer...
,I/UEI.SmartControl( 5057): QS lib stop result = true
I/jxcore-log( 5327): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5327): 
I/art     ( 5888): CheckpointMarkThreadRoots callback created = 0xb0543500
D/UEI.SmartControl( 5057): QS shutdown complete
,I/NetworkMonitor( 5794): type=WIFI subType= reason=null isConnected=true
D/NativeLibraryUtils( 5949): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  904): Process com.lge.email (pid 5855) has died
I/PhoneApp( 1743): onTrimMemory: 15
I/PhoneApp( 1743): trim memory
,I/NetworkMonitor( 5794): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  904): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6020 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/jxcore-log( 5327): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5327): 
D/MonthWidgetProvider( 5979): [onReceive]
D/CalendarWidgetProvider( 5979): [onReceive]
D/CalendarWidgetProvider( 5979): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
W/HolidayIntentService( 5979): onHandleIntent
D/CalendarTypeController( 5979): [onUpdateAndInitCalendarTime]
D/HolidayDataLoader( 5979): readJsonAsset : holiday.json
,I/jxcore-log( 5327): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5327): 
D/WeekWidgetProvider( 5979): [onReceive]
D/CalendarWidgetProvider( 5979): [onReceive]
D/CalendarWidgetProvider( 5979): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5979): [onUpdateAndInitCalendarTime]
D/WeatherAncestor( 2763): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:29:18
,D/CAR.SERVICE( 5949): Connecting to CarCallService...
D/UpdateThreadPoolManager( 2763): 2 : This is isUpdating : false
D/Weather_cast( 2763): 2 : set auto-update time : 1/29 14:29
D/WeatherAncestor( 2763): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:29:18
D/WeatherService( 2763): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
,E/HolidayIntentService( 5979): onHandleIntent:holiday data empty
,I/ActivityManager(  904): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6040 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ActivityManager(  904): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2763): 2 : Utils getTopActivity com.lge.launcher2 / true
I/jxcore-log( 5327): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5327): 
,D/WeatherService( 2763): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2763): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/art     ( 5949): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5949): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/GHttpClientFactory( 5794): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 5794): Using platform SSLCertificateSocketFactory
,I/jxcore-log( 5327): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5327): 
I/art     ( 5544): CheckpointMarkThreadRoots callback created = 0xaaeec7d0
I/jxcore-log( 5327): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5327): 
W/ResourcesManager( 6020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6020): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6020): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/TimeService( 6040): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454063359114
D/        ( 6040): TimeServiceNative: User Time to be set is 1454063359114
D/QC-time-services( 6040): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6040): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6040): Lib:time_genoff_operation: pargs->ts_val = 1454063359114
D/QC-time-services( 6040): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  348): Daemon: Connection accepted:time_genoff
D/QC-time-services(  348): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454063359114
D/QC-time-services(  348): Daemon:genoff_opr: Base = 2, val = 1454063359114, operation = 0
D/QC-time-services(  348): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/11/70 14:30:51
,D/QC-time-services(  348): Daemon:Value read from RTC seconds = 13962651000
D/QC-time-services(  348): Daemon:new time 1454063359114 
D/QC-time-services(  348): Daemon: delta 1440100708114 genoff 1440100708114 
D/QC-time-services(  348): Daemon:genoff_persistent_update: Writing genoff = 1440100708114 to memory
D/QC-time-services(  348): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  348): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  348): Updating the TOD offset
D/QC-time-services(  348): Daemon:genoff_persistent_update: Writing genoff = 1440100708114 to memory
D/QC-time-services(  348): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  348): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  348): Daemon:Update to modem bit set
E/QC-time-services( 6040): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  348): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  348): Daemon: Base = 2, Value being sent to MODEM = 1124135908114
E/QC-time-services(  348): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  348): Daemon: Time-services: Waiting to acceptconnection
I/NotificationManager( 5888): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
I/art     ( 5544): CheckpointMarkThreadRoots callback created = 0xaaeec790
,I/NotificationManager( 5794): com.google.android.music: cancel(1061) by com.google.android.music
I/CheckinService( 4023): Checkin interval check for package: unspecified last checkin: 1454056149402 min interval config: 0 actual interval: 7209783
I/NotificationManager(  904): android: cancelAsUser(2145784878) by android
W/art     ( 5888): Suspending all threads took: 19.334ms
,D/CAR.SERVICE( 5949): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5949): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5949): Creating a new PhoneAdapter instance
W/ActivityManager(  904): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5949): setListener: com.google.android.gms.car.dn@1237ad53
W/ActivityManager(  904): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5949): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5949): Starting CarCallService with initial phone null
D/CAR.SERVICE( 5949): Package validated; name: com.android.vending
,I/ActivityManager(  904): Process com.android.gallery3d (pid 5827) has died
I/NotificationManager( 5949): com.google.android.gms: cancel(10436) by com.google.android.gms
I/LGEmail ( 6020): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/NotificationManager( 5544): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5544): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/LGEmail ( 6020): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/art     ( 5544): Suspending all threads took: 8.434ms
,I/ActivityManager(  904): Process com.lge.clock (pid 5917) has died
,D/eas_req ( 6020): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  904): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6073 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6020): JNI_OnLoad()
I/HubEmail( 6020): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6020): registerNatives()
,I/HubEmail( 6020): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6020): registerNativeMethods()
I/HubEmail( 6020): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6020): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6020): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6073): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6073): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6073): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6073): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6073): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6073): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6073): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6073): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  904): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6097 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6073): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/art     (  313): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.330ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/LGDMClient( 6073): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 23.328ms
D/LGDMClient( 6073): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6073): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6073): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/NotificationManager(  904): android: cancelAsUser(2) by android
,D/LGDMClient( 6073): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.586ms
,I/AppUp4:AppBoxCP( 6097): onCreate
,W/AppUp4:DB( 6097):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6097):  setFingerPrint start
I/AppUp4:DB( 6097):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6097):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 6097):  SDK version = 0
I/AppUp4:DB( 6097):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6097): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6097): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6097): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6097): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6097): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6097): onReceive
I/AppUp4:CustModeStarterReceiver( 6097): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6097): Context : android.app.ReceiverRestrictedContext@2488b593
D/AppUp4:CustFacade( 6097): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6097): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6097): begin check event
I/AppUp4:CustModeStarterReceiver( 6097): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6097): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6097): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6097): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6097): handleAsyncCustNotification do not startCustService
I/LgeMiscReceiver( 3113): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3113): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3113): networkInfo.isConnected() = true
,D/PhoneState( 3113): setPdpRejectCasuse : false
I/ActivityManager(  904): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6119 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6119): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6119): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6119): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  904): Killing 5057:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  904): failed to open /acct/uid_10089/pid_5057/cgroup.procs: No such file or directory
,V/DownloadManager( 3135): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/PhoneMonitor( 6119): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6119): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6119): [parse] Load xml
V/TelephonyAutoProfiling( 6119): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6119): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6119): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/art     (  904): Explicit concurrent mark sweep GC freed 17454(765KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.138ms total 151.145ms
,I/CheckinService( 4023): Checkin interval check for package: unspecified last checkin: 1454056149402 min interval config: 0 actual interval: 7211509
V/DownloadManager( 3135): DownloadService onCreate
,I/NotificationManager( 3135): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3135): in removeSpuriousFiles
V/DownloadManager( 3135): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@64adf5c on behalf of 3135
I/DownloadManager( 3135): in trimDatabase
V/DownloadManager( 3135): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@3270b3a on behalf of 3135
I/ActivityManager(  904): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6143 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3135): DownloadService onStartCommand
I/CheckinService( 4023): Checking schedule, now: 1454063360971 next: 1454056179345
I/CheckinService( 4023): active receiver: enabled
V/DownloadManager( 3135): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@2a549548 on behalf of 3135
I/CheckinService( 4023): Preparing to send checkin request
,I/EventLogService( 4023): Accumulating logs since 1454062556484
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/DrmBroadcastReceiver( 6143): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6143): 1  network is available. Sync DRM Time with NTP
V/DownloadManager( 3135): DownloadService onDestroy
D/WeatherAncestor( 2763): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:29:21
,D/UpdateThreadPoolManager( 2763): 2 : This is isUpdating : false
V/DrmService( 6143): Service onCreate
D/DrmService( 6143): Received new request = 2
D/WeatherAncestor( 2763): connectivity changed - connection : true
D/Weather_cast( 2763): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 2763): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:29:21
D/WeatherService( 2763): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DrmSntpClient( 6143): Start Sync process
D/DrmSntpClient( 6143): Server : 0
I/qtaguid ( 5544): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5544): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5544): untagSocket(41) failed with errno -22
D/libc-netbsd( 6143): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6143): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6143): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6143): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  281): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  904): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6167 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  904): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2763): 2 : Utils getTopActivity com.lge.launcher2 / true
,V/AlarmManager(  904): ELAPSED_WAKEUP set : Alarm{f021ec8 type 2 when 98739 com.android.providers.calendar} when 98739
,D/WeatherService( 2763): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2763): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6167): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5544): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5544): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  904): Process com.google.android.music:main (pid 5794) has died
,I/CheckinRequestBuilder( 4023): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4023): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 5544): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5544): [1] DailyHygiene.access$600: Logging device features
,D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 6143): propertyValue:false
,V/AlarmManager(  904): RTC_WAKEUP set : Alarm{b7e5f74 type 0 when 1454063361566 com.android.vending} when 1454063361566
I/LGDrmClient( 6143): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  291): eDRM_SetDRMTime +++
I/LGDRM   (  291): [DRM] SET TIME : YR=2016, MON=1, DAY=29
I/LGDRM   (  291): [DRM] SET TIME : HR=10, MIN=29, SEC=20
V/ILGDrmService(  291): eDRM_SetDRMTime ---
,I/DrmSntpClient( 6143): Synched
D/DrmService( 6143): Completed !! request = 2
D/DrmService( 6143): Request count = 0
I/ActivityManager(  904): Process com.android.calendar (pid 5979) has died
V/DrmService( 6143): Service onDestroy
,D/DeviceConnectionService( 1733): client connected with version: 8296000
D/WearableService( 1733): callingUid 10006, callindPid: 1733
,D/Finsky  ( 5544): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5544): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/Babel_SMS( 6167): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6167): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6167): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6167): MmsConfig.loadFromDatabase
,W/art     ( 6167): Suspending all threads took: 5.645ms
,I/art     ( 4023): Explicit concurrent mark sweep GC freed 12830(1019KB) AllocSpace objects, 24(384KB) LOS objects, 25% free, 14MB/19MB, paused 1.307ms total 157.192ms
,E/Babel_SMS( 6167): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6167): MmsConfig.loadFromResources
I/art     ( 6167): CheckpointMarkThreadRoots callback created = 0xb042d710
E/Babel_SMS( 6167): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6167): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/art     ( 6167): CheckpointMarkThreadRoots callback created = 0xb042d6f0
,D/SensorManager( 6167): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6167): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6167): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6167): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6167): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6167): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6167): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6167): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6167): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6167): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6167): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6167): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6167): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6167): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6167): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6167): found sensor: Motion Accel, handle=46
,W/Settings( 6167): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6167): startup - clean
I/Babel   ( 6167): deleted: false for 0
,I/ActivityManager(  904): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6200 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6200): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6200): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6200): VM with version 2.1.0 has multidex support
I/MultiDex( 6200): install
I/MultiDex( 6200): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  904): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6217 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 6167): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6167): Unsupported mime audio/adpcm
W/AudioCapabilities( 6167): Unsupported mime audio/g726
W/AudioCapabilities( 6167): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6167): Unsupported mime audio/wma-voice
V/JNIHelp ( 6200): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/VideoCapabilities( 6167): Unsupported mime video/mjpg
,W/VideoCapabilities( 6167): Unsupported mime video/theora
,W/AudioCapabilities( 6167): Unsupported mime audio/evrc
,W/AudioCapabilities( 6167): Unsupported mime audio/qcelp
W/VideoCapabilities( 6167): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6167): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6167): Unsupported mime audio/qcelp
W/AudioCapabilities( 6167): Unsupported mime audio/evrc
,W/VideoCapabilities( 6167): Unsupported mime video/mp4v-esdp
,W/ActivityThread( 6200): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6200): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@bc1bdf4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6200): Installed default security provider GmsCore_OpenSSL
I/VideoCapabilities( 6167): Unsupported profile 4 for video/mp4v-es
I/NotificationManager( 6200): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6200): com.google.android.gms: cancel(39789) by com.google.android.gms
W/VideoCapabilities( 6167): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6167): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6167): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6167): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6167): onServiceConnected
,W/Babel   ( 6167): Attempted to change video mute state without an active call.
I/NotificationManager( 6167): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6167): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/art     ( 6200): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6200): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/libc-netbsd( 6167): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6167): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6167): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  281): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 6167): propertyValue:false
I/Babel   ( 6167): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  904): Killing 6040:com.qualcomm.timeservice/1000 (adj 15): empty #11
D/NativeLibraryUtils( 6200): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  904): failed to open /acct/uid_1000/pid_6040/cgroup.procs: No such file or directory
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6217): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,D/WVCdm   (  286): Instantiating CDM.
I/WVCdm   (  286): CdmEngine::OpenSession
I/WVCdm   (  286): Level3 Library Dec 11 2014 16:13:16
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6217): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6217): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 6217): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6217):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6217):   adb logcat -s GAv4
W/WVCdm   (  286): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  286): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  286): L1 library not specified. Falling Back to L3
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6217): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WVCdm   (  286): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  286): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  286): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  286): CdmEngine::GenerateKeyRequest
D/WVCdm   (  286): PrepareKeyRequest: nonce=1369569331
,V/AlarmManager(  904): ELAPSED_WAKEUP set : Alarm{3b52fe41 type 2 when 100743 com.google.android.gms} when 100743
W/GAv4    ( 6217): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6217): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6217): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/art     ( 6200): CheckpointMarkThreadRoots callback created = 0xaaf162a0
,I/art     ( 6200): CheckpointMarkThreadRoots callback created = 0xaaf16290
,I/dex2oat ( 6271): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/WebViewFactory( 6217): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/dex2oat ( 6271): dex2oat took 161.732ms (threads: 4)
,I/Adreno-EGL( 6200): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6200): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6200): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6200): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6200): Remote Branch: 
I/Adreno-EGL( 6200): Local Patches: 
I/Adreno-EGL( 6200): Reconstruct Branch: 
,I/LibraryLoader( 6217): Time to load native libraries: 2 ms (timestamps 1348-1350)
I/LibraryLoader( 6217): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6217): Binding Chromium to main looper Looper (main, tid 1) {224a8c24}
I/LibraryLoader( 6217): Expected native library version number "",actual native library version number ""
,I/chromium( 6217): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6217): Initializing chromium process, singleProcess=true
,W/art     ( 6217): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6217): ApplicationContext is null in ApplicationStatus
,W/chromium( 6217): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6217): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6217): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6217): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6217): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6217): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6217): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6217): Remote Branch: 
I/Adreno-EGL( 6217): Local Patches: 
I/Adreno-EGL( 6217): Reconstruct Branch: 
V/AudioPolicyService(  286): registerClient() client 0xb385dd20, uid 10079
W/AudioManagerAndroid( 6217): Requires BLUETOOTH permission
,I/WVCdm   (  286): CdmEngine::OpenSession
I/ActivityManager(  904): Process com.google.android.apps.plus (pid 5888) has died
,I/NSApplication( 6217): Starting up...
,I/ActivityManager(  904): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6299 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  904): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6323 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 6020:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  904): failed to open /acct/uid_10021/pid_6020/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 5949): mConnectedToCar = false, abort
,W/ResourcesManager( 6323): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/ActivityThread( 5949): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@219d5ddb that was originally bound here
E/ActivityThread( 5949): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@219d5ddb that was originally bound here
E/ActivityThread( 5949): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5949): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5949): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5949): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5949): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5949): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5949): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5949): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5949): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5949): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5949): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5949): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5949): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5949): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5949): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5949): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5949): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5949): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5949): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5949): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5949): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5949): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5949): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 5949): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@33853942 that was originally bound here
E/ActivityThread( 5949): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@33853942 that was originally bound here
E/ActivityThread( 5949): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5949): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5949): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5949): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5949): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5949): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5949): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5949): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5949): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5949): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5949): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5949): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5949): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5949): 	at android.app.ActivityThread.acce,ss$1900(ActivityThread.java:155)
E/ActivityThread( 5949): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5949): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5949): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5949): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5949): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5949): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5949): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5949): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  904): Unbind failed: could not find connection for android.os.BinderProxy@4a20f7a
I/ActivityManager(  904): Process com.lge.appbox.client (pid 6097) has died
,I/iu.SyncManager( 4023): SYNC; picasa accounts
,D/NetworkLogImpl( 4023): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4023): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 4023): num queued entries: 0
,I/iu.UploadsManager( 4023): num updated entries: 0
I/iu.SyncManager( 4023): NEXT; no task
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
I/rmt_storage(  278): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  278): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  278): wakelock acquired: 1, error no: 42
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/ActivityManager(  904): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6357 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out( 1733): propertyValue:false
I/WVCdm   (  286): CdmEngine::CloseSession
,I/WVCdm   (  286): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  286): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  286): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  286): CdmEngine::GenerateKeyRequest
D/WVCdm   (  286): PrepareKeyRequest: nonce=3586412126
I/ActivityManager(  904): Process com.google.android.gms:car (pid 5949) has died
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  278): 
I/rmt_storage(  278): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DigitalAppWidgetProvider( 6357): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2763): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 11:29:25
D/UpdateThreadPoolManager( 2763): 2 : This is isUpdating : false
D/Weather_cast( 2763): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2763): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 11:29:25
D/WeatherService( 2763): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  904): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2763): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2763): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2763): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/LocationInitializer( 4023): Restart initialization of location
E/MDM     ( 1733): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  904): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6381 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,W/ResourcesManager( 6381): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/GCM     ( 1733): GCM config loaded
,D/CalendarProvider2( 6381): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@b8d2d91
,D/CalendarProvider2( 6381): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6381): Created com.android.providers.calendar.CalendarAlarmManager@6503a82(com.android.providers.calendar.CalendarProvider2@b8d2d91)
D/CalendarProviderBroadcastReceiver( 6381): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6381): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6381): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6381): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6381): [getOrCreateCalendarAlarmManager]
,D/Finsky  ( 5544): [669] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,E/MDM     ( 1733): [103] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4023): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,I/ActivityManager(  904): Process com.google.android.setupwizard (pid 6119) has died
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  904): android: cancelAsUser(2) by android
I/art     (  904): Explicit concurrent mark sweep GC freed 21753(1048KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.671ms total 172.060ms
,D/CalendarProvider2( 6381): [IntentService] Release Lock
,D/CalendarProvider2( 6381): CalendarProviderIntentService.onDestroy()
,D/libc-netbsd( 5544): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5544): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5544): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5544): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 5544): propertyValue:false
I/WVCdm   (  286): CdmEngine::CloseSession
I/WVCdm   (  286): L3 Terminate.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/jxcore-log( 5327): Test app app.js loaded
I/jxcore-log( 5327): 
,I/Adreno-EGL( 6200): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6200): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6200): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6200): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6200): Remote Branch: 
I/Adreno-EGL( 6200): Local Patches: 
I/Adreno-EGL( 6200): Reconstruct Branch: 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 5327): BLE advertisement is supported
I/jxcore-log( 5327): 
I/Adreno-EGL( 6200): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6200): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6200): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6200): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6200): Remote Branch: 
I/Adreno-EGL( 6200): Local Patches: 
I/Adreno-EGL( 6200): Reconstruct Branch: 
,I/chromium( 5327): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/CheckinRequestBuilder( 4023): Classify the device as Phone.
,D/libc-netbsd( 4023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 4023): propertyValue:false
D/libc-netbsd( 4023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinTask( 4023): Sending checkin request (9845 bytes)
I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/InputReader(  904): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  904): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6450 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/CheckinResponseProcessor( 4023): From server: 1 gservices updates and 0 deletes
,D/administrator(  904): Handling package changes for user 0
I/NotificationManager( 6167): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6167): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6167): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6167): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 6450): onCreate
,W/AppUp4:DB( 6450):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6450):  setFingerPrint start
,I/AppUp4:DB( 6450):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6450):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 6450):  SDK version = 0
I/AppUp4:DB( 6450):  beforefinger == newfinger no write in DB
W/System  ( 6167): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6167): Installed default security provider GmsCore_OpenSSL
D/AppUp4:AppBoxApplication( 6450): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6450): onReceive
I/AppUp4:CustModeStarterReceiver( 6450): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6450): Context : android.app.ReceiverRestrictedContext@3f18db64
D/AppUp4:CustFacade( 6450): isCustomizationCompleted : false
,I/ActivityManager(  904): Process com.lge.lgdmsclient (pid 6073) has died
,D/AppUp4:CustFacade( 6450): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6450): begin check event
I/AppUp4:CustModeStarterReceiver( 6450): Event For Nothing, skip.
I/NotificationService(  904): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  904): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  904): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  904): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  904): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6473 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
I/art     (  313): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 312us total 21.795ms
,I/CertBlacklister(  904): Certificate blacklist changed, updating...
I/CertBlacklister(  904): Certificate blacklist updated
I/GservicesProvider( 5750): main difference update completed
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 21.675ms
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.747ms
,W/ResourcesManager(  904): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  904): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  904): Process com.google.android.apps.magazines (pid 6217) has died
I/CheckinRequestBuilder( 4023): Checkin reason type: 8 attempt count: 1
,V/BackupManagerService(  904): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
E/ActivityThread( 4023): Failed to find provider info for com.google.android.wearable.settings
V/BackupManagerService(  904): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2784036d
,W/ResourcesManager( 6473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6473): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6473): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/ActivityManager(  904): Process com.lge.drmservice (pid 6143) has died
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  904): applying state to connected service
,I/ActivityManager(  904): Process com.google.android.apps.plus (pid 6323) has died
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AppConfig( 6473): Total System Memory = 906309632
I/GalleryUtils( 6473): Application Heap = 96 MB
I/AppConfig( 6473): App Tier : NOT_DEF
,D/SystemHelper( 6473): region [EU], country [EU], operator [OPEN], sub-operator []
I/CheckinRequestBuilder( 4023): Classify the device as Phone.
,I/ActivityManager(  904): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6497 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/CheckinTask( 4023): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4023): Checking schedule, now: 1454063372280 next: 1454590621265
I/CheckinService( 4023): active receiver: disabled
,D/CheckinService( 4023): Recording last checkin time for package unspecified as 1454063372312
,W/ResourcesManager( 6497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6497): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6497): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6497): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6497): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6497): BUILD Country: EU
I/SystemConfig( 6497): BUILD Operator: OPEN
,I/ActivityManager(  904): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6523 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6497): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6497): existFile = false
I/SystemConfig( 6497): canReadFile = false
I/SystemConfig( 6497): systemFeature RCS result false
D/SystemConfig( 6497): refreshRcsSupport() :false
,I/LockScreenSettings( 6523): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6523): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6523): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6523): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6523): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6523): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  904): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6540 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 6299:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  904): failed to open /acct/uid_10048/pid_6299/cgroup.procs: No such file or directory
,W/ResourcesManager( 6540): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  904): Killing 6357:com.lge.clock/u0a10 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 82 ms] updated apps [took 81 ms] 
W/libprocessgroup(  904): failed to open /acct/uid_10010/pid_6357/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 4023): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  904): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6566 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/PackageBroadcastService( 4023): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4023): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  904): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6594 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,E/UpdateRequestReceiver( 6594): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6594): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6594): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6594): Received malformed URL while handling Gservices.CHANGED_ACTION
I/CheckinService( 4023): Checkin interval check for package: unspecified last checkin: 1454063372312 min interval config: 0 actual interval: 1304
,I/CheckinService( 4023): Checking schedule, now: 1454063373638 next: 1454590621265
I/CheckinService( 4023): active receiver: disabled
,I/art     (  904): Explicit concurrent mark sweep GC freed 25279(1307KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.975ms total 154.894ms
I/GservicesUpdateTask( 1936): Updating Gservices keys
I/SystemUpdateService( 4023): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 4023): onCreate
D/SystemUpdateService( 4023): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 4023): cancelUpdate (empty URL)
,I/SystemUpdateService( 4023): active receiver: disabled
I/NotificationManager( 4023): com.google.android.gms: cancel(2130838165) by com.google.android.gms
I/NotificationManager( 4023): com.google.android.gms: cancel(2130838166) by com.google.android.gms
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/art     ( 5750): Explicit concurrent mark sweep GC freed 10033(491KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 440us total 59.458ms
,I/GStaticConfiguration( 1936): #getNewConfigurationUrl [pref=2015_09_15_14_04_18, gservice=2016_01_27_20_58_17]
,D/libc-netbsd( 1936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  281): [LG DATA] No such appUid: 10042
D/DnsProxyListener(  281): App 10042 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/art     ( 4023): Explicit concurrent mark sweep GC freed 33218(2023KB) AllocSpace objects, 17(272KB) LOS objects, 24% free, 14MB/19MB, paused 1.098ms total 105.128ms
,I/ActivityManager(  904): Process com.android.gallery3d (pid 6473) has died
,I/art     ( 5750): Explicit concurrent mark sweep GC freed 3103(126KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 381us total 24.016ms
,D/SystemUpdateService( 4023): onDestroy
,E/DynamiteModule( 4023): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 4023): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 4023): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 4023): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 4023): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 4023): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 4023): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 4023): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 4023): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 4023): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 4023): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 4023): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 4023): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 4023): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 4023): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 4023): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 4023): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 4023): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 4023): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 4023): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 4023): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 4023): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 4023): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 4023): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 4023): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 4023): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 4023): 		... 17 more
E/DynamiteModule( 4023): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/DynamiteModule( 4023): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 4023): Selected local version of com.google.android.gms.flags
D/SystemEventReceiver( 4023): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 4023): Updating ocr activity enabled=false
,W/ActivityManager(  904): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 4023): Updating downloaded model state (gservices changed)
,I/NotificationManager(  904): android: cancelAsUser(-591465577) by android
I/art     ( 5750): Explicit concurrent mark sweep GC freed 2720(108KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 734us total 26.109ms
,I/Icing   ( 4023): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 21902(1447KB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 13MB/22MB, paused 1.688ms total 83.149ms
,D/Icing   ( 4023): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 4023): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/GCM     ( 1733): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/ActivityManager(  904): Killing 6381:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  904): failed to open /acct/uid_10014/pid_6381/cgroup.procs: No such file or directory
V/AlarmManager(  904): RTC_WAKEUP set : Alarm{3872f3dc type 0 when 1454063374764 com.android.vending} when 1454063374764
,D/Finsky  ( 5544): [660] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5544): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/GCoreUlr( 1733): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1733): DispatchingService.onCreate()
I/ActivityManager(  904): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6676 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
,I/GCoreUlr( 1733): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
E/ctxmgr  ( 1733): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,D/PhoneMonitor( 6676): Register our PhoneStateListener
,V/SetupWizard( 6676): Connected to Gservices successfully
,I/art     ( 5750): Explicit concurrent mark sweep GC freed 2570(102KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 3.995ms total 50.269ms
W/ctxmgr  ( 1733): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
E/ctxmgr  ( 1733): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,D/PhoneMonitor( 6676): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/ActivityManager(  904): Killing 6450:com.lge.appbox.client/u0a11 (adj 15): empty #11
,V/TelephonyAutoProfiling( 6676): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6676): [parse] Load xml
V/TelephonyAutoProfiling( 6676): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6676): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6676): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/ContextImpl( 3391): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,W/libprocessgroup(  904): failed to open /acct/uid_10011/pid_6450/cgroup.procs: No such file or directory
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/GCoreUlr( 1733): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1733): Unbound from all location providers
I/GCoreUlr( 1733): Place inference reporting - stopped
I/GCoreUlr( 1733): DispatchingService.onDestroy()
I/GCoreUlr( 1733): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1733): Unbound from all location providers
I/GCoreUlr( 1733): Place inference reporting - stopped
W/SQLiteConnectionPool( 4023): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/MusicWidget( 2678): mDelayedStopHandler : unbind
,I/MusicBrowser( 2781): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2781): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2781): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2781): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2781): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2781): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2781): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2781): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  904):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@279bc700com.lge.music.MediaPlaybackService$6@3df5eb39
,D/MusicBrowser( 2781): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2781): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2781): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2781): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2781): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@ff17ef
,I/MusicBrowser( 2781): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2781): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2781): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2781): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2781): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2781): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2781): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2781): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2781): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2781): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2781): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2781): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2781): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2781): reset
V/MediaPlayer[Native]( 2781): setListener
,V/MediaPlayer[Native]( 2781): disconnect
V/MediaPlayer[Native]( 2781): destructor
V/AudioFlinger(  286): releasing 19 from 2781 for -1
V/AudioFlinger(  286):  decremented refcount to 0
V/AudioFlinger(  286): purging stale effects
I/ActivityManager(  904): Killing 6167:com.google.android.talk/u0a61 (adj 15): empty #11
V/MediaPlayer[Native]( 2781): disconnect
,D/MusicBrowser( 2781): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2781): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2781): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2781): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2781): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2781): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2781): [SmartShareManagerClient] unregisterListener: 913749374
W/SmartShareClient( 2781): [SmartShareManagerClient] unregisterListener invalid listener: 913749374
I/SmartShareClient( 2781): [SmartShareManagerClient] terminate service: 2781/MediaPlaybackService/63312333
E/HomeCloudIF( 2781): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2781): [SmartShareManagerClient] unbindService context:android.app.Application@394bdadf
W/libprocessgroup(  904): failed to open /acct/uid_10061/pid_6167/cgroup.procs: No such file or directory
,V/CloudHub( 2781): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2781): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2781): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2781): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2781): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  904): Killing 6497:com.android.contacts/u0a18 (adj 15): empty #11
I/CloudHub( 2781): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
W/libprocessgroup(  904): failed to open /acct/uid_10018/pid_6497/cgroup.procs: No such file or directory
,D/sensors_hal_Time(  904): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  904): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  904): tsOffsetIs: Apps: 114304392305; DSPS: 3844260; Offset : -3017713747
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/InputReader(  904): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/ActivityManager(  904): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6740 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/administrator(  904): Handling package changes for user 0
,W/ResourcesManager( 6740): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(  904): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationService(  904): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  904): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  904): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  904): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  904): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  904): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@80bd8fc
W/ResourceType(  904): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  904): applying state to connected service
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 20269(1179KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 13MB/23MB, paused 1.256ms total 84.139ms
,I/Babel_SMS( 6740): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6740): MmsConfig.loadMmsSettings
I/Babel_SMS( 6740): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6740): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6740): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6740): MmsConfig.loadFromResources
E/Babel_SMS( 6740): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6740): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/ActivityManager(  904): Process com.google.android.apps.plus (pid 6540) has died
,D/SensorManager( 6740): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6740): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6740): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6740): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6740): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6740): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6740): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6740): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6740): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6740): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6740): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6740): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6740): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6740): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6740): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6740): found sensor: Motion Accel, handle=46
W/Settings( 6740): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6740): startup - clean
I/art     ( 6740): CheckpointMarkThreadRoots callback created = 0xaaf45450
I/Babel   ( 6740): deleted: false for 0
,I/art     ( 6740): CheckpointMarkThreadRoots callback created = 0xaaf45430
,W/AudioCapabilities( 6740): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6740): Unsupported mime audio/adpcm
W/AudioCapabilities( 6740): Unsupported mime audio/g726
,W/AudioCapabilities( 6740): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6740): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6740): Unsupported mime video/mjpg
W/VideoCapabilities( 6740): Unsupported mime video/theora
I/ActivityManager(  904): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6776 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 6740): Unsupported mime audio/evrc
W/AudioCapabilities( 6740): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6740): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6740): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6740): Unsupported mime audio/qcelp
W/AudioCapabilities( 6740): Unsupported mime audio/evrc
,W/VideoCapabilities( 6740): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6740): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6740): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:AppBoxCP( 6776): onCreate
W/VideoCapabilities( 6740): Unrecognized profile 2130706433 for video/avc
W/AppUp4:DB( 6776):  [AppBoxDatabaseHelper] construct
W/VideoCapabilities( 6740): Unrecognized profile 2130706433 for video/avc
I/AppUp4:DB( 6776):  setFingerPrint start
,I/AppUp4:DB( 6776):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
W/VideoCapabilities( 6740): Unrecognized profile 2130706433 for video/avc
I/AppUp4:DB( 6776):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6776):  SDK version = 0
I/AppUp4:DB( 6776):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6776): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6776): onReceive
I/AppUp4:CustModeStarterReceiver( 6776): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6776): Context : android.app.ReceiverRestrictedContext@3f18db64
D/AppUp4:CustFacade( 6776): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6776): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6776): begin check event
I/AppUp4:CustModeStarterReceiver( 6776): Event For Nothing, skip.
I/ActivityManager(  904): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6797 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/PackageSettings(  904): Skipping PackageSetting{3e7db044 com.example.hello/10317} due to missing metadata
,I/vclib   ( 6740): onServiceConnected
W/Babel   ( 6740): Attempted to change video mute state without an active call.
I/NotificationManager( 6740): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 6797): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6797): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6797): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6740): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6740): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6740): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 6740): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6740): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6740): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 6797): Total System Memory = 906309632
I/GalleryUtils( 6797): Application Heap = 96 MB
,I/AppConfig( 6797): App Tier : NOT_DEF
,D/SystemHelper( 6797): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  904): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6820 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 6523:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  904): failed to open /acct/uid_10069/pid_6523/cgroup.procs: No such file or directory
,W/ResourcesManager( 6820): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6820): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6820): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6820): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6820): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6820): BUILD Country: EU
I/SystemConfig( 6820): BUILD Operator: OPEN
,I/art     (  904): Explicit concurrent mark sweep GC freed 38101(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 2.404ms total 169.834ms
,I/ActivityManager(  904): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6842 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 6566:com.google.android.partnersetup/u0a9 (adj 15): empty #11
I/art     (  313): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 21.216ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.325ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.954ms
,W/libprocessgroup(  904): failed to open /acct/uid_10009/pid_6566/cgroup.procs: No such file or directory
I/SystemConfig( 6820): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6820): existFile = false
I/SystemConfig( 6820): canReadFile = false
I/SystemConfig( 6820): systemFeature RCS result false
D/SystemConfig( 6820): refreshRcsSupport() :false
I/LockScreenSettings( 6842): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6842): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6842): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 6842): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6842): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6842): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  904): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6859 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  904): Killing 6594:com.google.android.configupdater/u0a3 (adj 15): empty #11
,W/libprocessgroup(  904): failed to open /acct/uid_10003/pid_6594/cgroup.procs: No such file or directory
,W/ResourcesManager( 6859): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 4023): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4023): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4023): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 65 ms] updated apps [took 65 ms] 
,D/charger_monitor(  489): init target 500000
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  489): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  904): battery changed pluggedType: 2
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  904): battery changed pluggedType: 2
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Icing   ( 4023): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,V/AlarmManager(  904): ELAPSED_WAKEUP set : Alarm{272449af type 2 when 123424 android} when 123424
,I/Icing   ( 4023): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  904): Killing 6200:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  904): failed to open /acct/uid_10006/pid_6200/cgroup.procs: No such file or directory
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/CloudHub( 2781): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19973
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  904): Killing 6676:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  904): failed to open /acct/uid_10038/pid_6676/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/charger_monitor(  489): init target 500000
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/charger_monitor(  489): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  904): battery changed pluggedType: 2
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  904): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  904): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  904): tsOffsetIs: Apps: 134305193182; DSPS: 4499647; Offset : -3017736585
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
,I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
,I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/PowerManagerServiceEx(  904): acquireWakeLockInternal: lock=583393474, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=904
,D/WeatherService( 2763): 2 : TimeTick Intent has been received, Time(hour:min:sec) 11:30:0
D/WeatherService( 2763): 2 : TimeTick Intent And Screen On
D/WeatherService( 2763): 2 : SDK version : 21
W/ActivityManager(  904): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2763): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2763): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2763): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2763): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2763): 2 : This is isUpdating : false
D/WeatherService( 2763): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2763): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2763): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2763): 2 : Fixed theme : optimus
D/WeatherReflect( 2763): 2 : Map key string is -2
,D/lim     ( 2763): 2 : time = 11:30
I/WeatherReflect( 2763): Model Name : LG-D722
D/WeatherTheme( 2763): 2 : Different view - status_min_formatted : 29 != 30
D/WeatherTheme( 2763): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2763): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2763): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2763): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2763): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2763): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/Weather4x2_optimus( 2763): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
,D/Weather4x2_optimus( 2763): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2763): forecast size is 0
D/Theme   ( 2763): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2763): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2763): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2763): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2763): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2763): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2763): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2763): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2763): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2763): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2763): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2763): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2763): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2763): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2763): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2763): url is : null
D/Theme   ( 2763): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2763): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2763): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2763): 2 : update view, appWidgetId: 2
D/WeatherService( 2763): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 11:30:0
,D/PowerManagerServiceEx(  904): releaseWakeLockInternal: lock=583393474 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  904): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6923 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/DigitalAppWidgetProvider( 6923): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6923): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3f18db64
I/ActivityManager(  904): Killing 2781:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  286): 2781 died, releasing its sessions
V/AudioFlinger(  286):  pid 1743 @ 0
,V/AudioFlinger(  286):  pid 3113 @ 1
V/AudioFlinger(  286):  pid 3113 @ 2
W/libprocessgroup(  904): failed to open /acct/uid_10028/pid_2781/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  904): ELAPSED_WAKEUP set : Alarm{2540e1bc type 2 when 142997 com.google.android.gms} when 142997
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1454063405640 tag=VacuumService
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 5790 seconds from now (1454063406061)
,D/GetConfigurationSnapshotOperation( 1733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  904): android: cancelAsUser(2) by android
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  904): ALS enabled for SRE
,D/PowerManagerServiceEx(  904): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28656 ms ago)
D/qdlights(  904): set_light_backlight: 253
,D/qdlights(  904): set_light_backlight: 250
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/qdlights(  904): set_light_backlight: 246
,D/qdlights(  904): set_light_backlight: 243
,D/qdlights(  904): set_light_backlight: 240
,D/qdlights(  904): set_light_backlight: 236
,D/qdlights(  904): set_light_backlight: 233
,D/qdlights(  904): set_light_backlight: 230
,D/qdlights(  904): set_light_backlight: 226
,D/qdlights(  904): set_light_backlight: 223
,D/qdlights(  904): set_light_backlight: 220
,D/qdlights(  904): set_light_backlight: 216
,D/qdlights(  904): set_light_backlight: 213
,D/qdlights(  904): set_light_backlight: 210
,D/qdlights(  904): set_light_backlight: 206
,D/qdlights(  904): set_light_backlight: 203
,D/qdlights(  904): set_light_backlight: 200
,D/qdlights(  904): set_light_backlight: 196
,D/qdlights(  904): set_light_backlight: 193
,D/qdlights(  904): set_light_backlight: 190
,D/qdlights(  904): set_light_backlight: 186
,D/qdlights(  904): set_light_backlight: 183
,D/qdlights(  904): set_light_backlight: 180
,D/qdlights(  904): set_light_backlight: 176
,D/qdlights(  904): set_light_backlight: 173
,D/qdlights(  904): set_light_backlight: 170
,D/qdlights(  904): set_light_backlight: 166
,D/qdlights(  904): set_light_backlight: 163
,D/qdlights(  904): set_light_backlight: 160
,D/qdlights(  904): set_light_backlight: 156
,D/qdlights(  904): set_light_backlight: 153
,D/qdlights(  904): set_light_backlight: 150
,D/qdlights(  904): set_light_backlight: 146
,D/qdlights(  904): set_light_backlight: 143
,D/qdlights(  904): set_light_backlight: 140
,D/qdlights(  904): set_light_backlight: 136
,D/qdlights(  904): set_light_backlight: 133
,D/qdlights(  904): set_light_backlight: 130
,D/qdlights(  904): set_light_backlight: 126
,D/qdlights(  904): set_light_backlight: 123
,D/qdlights(  904): set_light_backlight: 120
,D/qdlights(  904): set_light_backlight: 116
,D/qdlights(  904): set_light_backlight: 113
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  904): set_light_backlight: 110
,D/qdlights(  904): set_light_backlight: 106
,D/qdlights(  904): set_light_backlight: 103
,D/qdlights(  904): set_light_backlight: 100
,D/qdlights(  904): set_light_backlight: 96
,D/qdlights(  904): set_light_backlight: 93
,D/qdlights(  904): set_light_backlight: 90
,D/qdlights(  904): set_light_backlight: 86
,D/qdlights(  904): set_light_backlight: 83
,D/qdlights(  904): set_light_backlight: 80
,D/qdlights(  904): set_light_backlight: 76
,D/qdlights(  904): set_light_backlight: 73
,D/qdlights(  904): set_light_backlight: 70
,D/qdlights(  904): set_light_backlight: 66
,D/qdlights(  904): set_light_backlight: 63
,D/qdlights(  904): set_light_backlight: 60
,D/qdlights(  904): set_light_backlight: 56
,D/qdlights(  904): set_light_backlight: 53
,D/qdlights(  904): set_light_backlight: 50
,D/qdlights(  904): set_light_backlight: 46
,D/qdlights(  904): set_light_backlight: 43
,D/qdlights(  904): set_light_backlight: 40
,D/qdlights(  904): set_light_backlight: 36
,D/qdlights(  904): set_light_backlight: 33
,D/qdlights(  904): set_light_backlight: 30
,D/qdlights(  904): set_light_backlight: 26
,D/qdlights(  904): set_light_backlight: 23
,D/qdlights(  904): set_light_backlight: 20
,D/qdlights(  904): set_light_backlight: 16
,D/qdlights(  904): set_light_backlight: 13
,D/qdlights(  904): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  904): ELAPSED_WAKEUP set : Alarm{2d7ad284 type 2 when 153443 android} when 153443
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,E/ActivityThread( 4023): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  904): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 123806, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  904): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 214418, reason: UserStart
I/NotificationManager(  904): android: cancelAsUser(716319171) by android
D/sensors_hal_Time(  904): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  904): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  904): tsOffsetIs: Apps: 154306036509; DSPS: 5155034; Offset : -3017716868
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  904): ALS enabled for SRE
D/PowerManagerServiceEx(  904): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35651 ms ago)
,I/PowerManagerService(  904): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  904): ALS enabled for SRE
D/PowerManagerServiceEx(  904): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35664 ms ago)
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  904): Sleeping (uid 1000)...
D/LPWGController(  904): [updateScreenState] screen on = false
D/LPWGController(  904): disable proximity sensor
,D/LPWGController(  904): enable proximity sensor
I/SensorManager(  904): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@27e069] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  904): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  904): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  904): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  904): activate: handle is 48, enable
V/sensors_hal_Ctx(  904): activate sensors is 1400000000000
D/sensors_hal_Thresh(  904): enable: handle=48
I/sensors_hal_SAM(  904): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  904): waitForResponse: timeout=1000
V/sensors_hal_SAM(  904): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  904): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  904): enable: Received response: 0
D/PowerManagerServiceEx(  904): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35704 ms ago)
I/Adreno-EGL(  904): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  904): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  904): Build Date: 03/02/15 Mon
I/Adreno-EGL(  904): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  904): Remote Branch: 
I/Adreno-EGL(  904): Local Patches: 
I/Adreno-EGL(  904): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (967 us)
,I/Sensors (  424): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  904): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  904): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  904): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  904): processInd: handle 48, count=1
V/sensors_hal_Thresh(  904): processInd:sensor android.sensor.proximity (wake_up),
I/sensors_hal_Thresh(  904): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  904): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  904): poll: count: 256
I/sensors_hal_Ctx(  904): poll: released wakelock sensor_ind
D/sensors_hal_Util(  904): waitForResponse: timeout=0
D/LPWGController(  904): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  904): current mode = 1  value = 1 1
I/LPWGController(  904): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  904): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  904): set_light_backlight: 0
,I/SensorManager(  904): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  904): activate: handle is 46, disable
V/sensors_hal_Ctx(  904): activate sensors is 1000000000000
D/sensors_hal_LP2(  904): enable: handle=46
D/sensors_hal_LP2(  904): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  904): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  904): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  904): Display changed displayId=0
V/sensors_hal_SAM(  904): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
,D/sensors_hal_LP2(  904): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1743): Display #0 changed.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
D/SurfaceControl(  904): Excessive delay in setPowerMode(): 221ms
,I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  904): Got set_interactive hint
,D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1331): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1373): notifyScreenOffLocked
D/SmartCoverViewMediator( 1331): notifyScreenOffLocked
D/SmartCoverViewMediator( 1331): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1373): handleNotifyScreenOff
,D/WifiServerServiceExt(  904): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  286): setParameters(): io 0, keyvalue screen_state=on, calling pid 904
I/WifiServerServiceExt(  904): set CMD_KT_SCAN_INTERVAL
D/audio_hw_primary(  286): adev_set_parameters: enter: screen_state=on
V/voice   (  286): voice_set_parameters: enter: screen_state=on
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: exit
V/voice   (  286): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  286): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  286): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  286): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  286): lge_platform_set_loopback_parameters: enter: 
D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
E/lge_audio_pcm_dump(  286): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  286): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  286): adev_set_parameters: exit with code(0)
D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
,D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/GpsLocationProvider(  904): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1842): |CORE| sendScreenState: state:true
I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): updateLightsLocked : turn off led
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1806): lockStatus = 0
D/LNfcService( 1788): action : android.intent.action.SCREEN_ON
D/LEDHandler( 1806): RESTART MSG
D/NfcServiceNXP( 1788): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1788): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1788): isRequireNfcCRouting() return true
D/LNfcService( 1788): isHCERoutingtoHost() return : true
D/NfcService( 1788): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): newParams.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): screenState= 3
D/NfcService( 1788): Discovery configuration equal, not updating.
,D/Ulp_jni (  904): JNI:system_update. Event-0
D/SplitWindow(  904): check instance of lgWin Window{1f47ee1c u0 SearchPanel}
,D/InputDispatcher(  904): Window went away: Window{1ac7643f u0 SearchPanel}
,I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
I/ActivityManager(  904): Process com.google.android.talk (pid 6740) has died
I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,V/PhoneApp( 1743): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2763): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:30:19
,D/WeatherService( 2763): 2 : ACTION screen on
D/WeatherService( 2763): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2763): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherService( 2763): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:30:19
D/AppCleanupService( 3844): android.intent.action.SCREEN_ON
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): ACTION_SCREEN_ON
V/AudioFlinger(  286): setParameters(): io 0, keyvalue screen_state=off, calling pid 904
D/audio_hw_primary(  286): adev_set_parameters: enter: screen_state=off
V/voice   (  286): voice_set_parameters: enter: screen_state=off
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: exit
V/voice   (  286): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  286): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  286): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  286): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  286): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  286): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  286): adev_set_parameters: exit with code(0)
D/WifiController(  904): CMD_SCREEN_OFF 
D/WifiController(  904): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  904): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1842): |CORE| sendScreenState: state:false
I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): updateLightsLocked : turn on led
E/LEDService( 1806): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1806): Can't handle this request of patternId:0
D/LEDHandler( 1806): RESTART MSG
D/VolumeVibrator( 1806): clear
I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1788): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1788): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1880): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1743): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2763): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:30:19
D/WeatherService( 2763): 2 : ACTION screen off
D/WeatherService( 2763): 2 : TimeTick Receiver Unregister
D/WeatherService( 2763): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:30:19
D/AppCleanupService( 3844): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3844): AppUsageStatsSaveTask
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): ACTION_SCREEN_OFF
,E/NxpNfcJni( 1788): getReconnectState = 0x0
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
D/LNfcService( 1788): isRequireNfcCRouting() return true
D/LNfcService( 1788): isHCERoutingtoHost() return : true
D/NfcService( 1788): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): newParams.techmask= mTechMask: 0
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
,D/NfcService( 1788): screenState= 1
E/NxpNfcJni( 1788): getReconnectState = 0x0
,I/Sensors (  424): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  904): ELAPSED_WAKEUP set : Alarm{1d51a25 type 2 when 161581 com.android.systemui} when 161581
,D/PhoneUtils( 1743): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
,V/TelecomServiceImpl( 1743): getCallState : 0
D/PhoneUtils( 1743): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
,D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  904): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  904): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  904): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  904): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  904): tsOffsetIs: Apps: 174306796344; DSPS: 5810419; Offset : -3017719842
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  904): ELAPSED_WAKEUP set : Alarm{135197fa type 2 when 182917 android} when 182917
,V/AlarmManager(  904): ELAPSED_WAKEUP set : Alarm{1b6811ab type 2 when 183475 android} when 183475
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,V/AlarmManager(  904): ELAPSED_WAKEUP set : Alarm{35f3d008 type 2 when 187000 com.google.android.gms} when 187000
,D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  904): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  904): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  904): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  904): tsOffsetIs: Apps: 194307552847; DSPS: 6465804; Offset : -3017726356
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  904): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  904): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  904): tsOffsetIs: Apps: 214308269090; DSPS: 7121187; Offset : -3017711966
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  904): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  904): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  904): tsOffsetIs: Apps: 234308946009; DSPS: 7776570; Offset : -3017737160
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  904): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  904): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  904): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  904): tsOffsetIs: Apps: 254309708553; DSPS: 8431954; Offset : -3017706621
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  904): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  904): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  904): tsOffsetIs: Apps: 274310479692; DSPS: 9087340; Offset : -3017729173
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  904): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  904): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  904): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  904): tsOffsetIs: Apps: 294311162028; DSPS: 9742722; Offset : -3017718406
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  904): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 5327): TAP version 13
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # multiplex can send data
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 1 String should be length:200
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # enqueue and run in order
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 2 firstPromise setTimeout
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 3 firstPromise result
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 4 firstPromise testValue
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 5 secondPromise setTimeout
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 6 secondPromise result
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 7 secondPromise testValue
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 8 thirdPromise in promise
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 9 thirdPromise result
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 10 thirdPromise testValue
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # basic
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 11 sane
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # another
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 12 sane
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 13 should be equal
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 14 null
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 15 (unnamed assert)
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 16 should be equal
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 17 should not throw
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 18 (unnamed assert)
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 19 (unnamed assert)
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 20 should not throw
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 21 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 22 should be equal
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 23 should be equal
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # failed to get mobile documents path
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 24 should be equal
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 25 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 26 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 27 should be equal
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #init should register the networkChanged event
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 28 should be equal
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #startBroadcasting should throw on null device name
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 29 should throw
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 30 should throw
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #startBroadcasting should throw on non-number port
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 31 should throw
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # #startBroadcasting should throw on NaN port
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 32 should throw
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # #startBroadcasting should throw on negative port
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 33 should throw
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # #startBroadcasting should throw on too large port
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 34 should throw
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 35 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 36 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 37 should be equal
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 38 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 39 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 40 should be equal
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 41 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 42 should be equal
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 43 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 44 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 45 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 46 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 47 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 48 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 49 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # should call Mobile("Disconnect") without an error
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 50 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 51 should be equal
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 52 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 53 should be equal
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063564735.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063564735.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5327): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
,D/LGBluetoothServiceAdapter( 1985): [BTUI] createSocketChannel FD=87 mFd=86
I/bt-btif ( 1985): BTA_JvRfcommStartServer
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: OK
I/io.jxcore.node.ConnectionHelper( 5327): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063564735.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): createAdvertiseData: From: 1454063564735.5327 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5327): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063564735.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): start: {"pi":"F8:95:C7:87:85:54","pn":"1454063564735.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454063564735.5327","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4fbf7a26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4fbf7a26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState add service
,D/LGWifiP2pService(  904): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): start: Starting P2P device discovery...
,D/LGWifiP2pService(  904): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063564735.5327
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  904): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5327): start: OK
I/wpa_supplicant( 5472): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1806): Event [CTRL-EVENT-SCAN-STARTED ]
I/jxcore-log( 5327): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 5327): 
I/io.jxcore.node.ConnectionHelper( 5327): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): onServerStopped
,I/bt-btif ( 1985): BTA_JvDeleteRecord
I/bt-btif ( 1985): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stop: Stopping peer discovery...
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothLeScanner( 5327): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): stop: Stopping services
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service
D/LGWifiP2pService(  904): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): stop: Stopping P2P device discovery...
,D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): P2P-FIND-STOPPED 
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: NOT_INITIALIZED
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5327): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5327): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 5327): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565008.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565008.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5327): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: OK
I/io.jxcore.node.ConnectionHelper( 5327): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565008.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): createAdvertiseData: From: 1454063565008.5327 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5327): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565008.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): start: {"pi":"F8:95:C7:87:85:54","pn":"1454063565008.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454063565008.5327","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Waiting for incoming connections...
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@10590bb2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@10590bb2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState add service
D/LGWifiP2pService(  904): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): start: Starting P2P device discovery...
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  904): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 5327): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565008.5327
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: OK
I/jxcore-log( 5327): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 5327): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/io.jxcore.node.ConnectionHelper( 5327): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): onServerStopped
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
I/bt-btif ( 1985): BTA_JvDeleteRecord
I/bt-btif ( 1985): BTA_JvRfcommStopServer
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stop: Stopping peer discovery...
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothLeScanner( 5327): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): stop: Stopping services
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): release: No more listeners, de-initializing...
D/LGWifiP2pService(  904): remove client information from framework
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5327): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 5327): 
D/LGWifiP2pService(  904): InactiveState{ when=-5ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-5ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5327): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565088.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565088.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5327): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: OK
I/io.jxcore.node.ConnectionHelper( 5327): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565088.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): createAdvertiseData: From: 1454063565088.5327 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5327): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565088.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): start: {"pi":"F8:95:C7:87:85:54","pn":"1454063565088.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454063565088.5327","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@865099a2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@865099a2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState add service
D/LGWifiP2pService(  904): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): start: Starting P2P device discovery...
,D/LGWifiP2pService(  904): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_WIFI
I/wpa_supplicant( 5472): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 5327): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565088.5327
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  904): discovery change broadcast true
I/jxcore-log( 5327): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 5327): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: Already running
I/io.jxcore.node.ConnectionHelper( 5327): stop
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): stopListeningForIncomingConnections: Stopping...
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): shutdown
I/bt-btif ( 1985): BTA_JvDeleteRecord
I/wpa_supplicant( 5472): P2P-FIND-STOPPED 
I/bt-btif ( 1985): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): onServerStopped
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stop: Stopping peer discovery...
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothLeScanner( 5327): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): stop: Stopping services
D/LGWifiP2pService(  904): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): discovery change broadcast false
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: No more listeners, de-initializing...
D/LGWifiP2pService(  904): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: NOT_STARTED
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service request
I/jxcore-log( 5327): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 5327): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5327): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565125.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565125.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5327): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: OK
I/io.jxcore.node.ConnectionHelper( 5327): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565125.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): createAdvertiseData: From: 1454063565125.5327 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5327): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565125.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): start: {"pi":"F8:95:C7:87:85:54","pn":"1454063565125.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454063565125.5327","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ee9b8db2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ee9b8db2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState add service
D/LGWifiP2pService(  904): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565125.5327
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: OK
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
D/LGWifiP2pService(  904): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: STARTED
I/wpa_supplicant( 5472): P2P-FIND-STOPPED 
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log( 5327): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 5327): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): discovery change broadcast false
I/io.jxcore.node.ConnectionHelper( 5327): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): onServerStopped
I/bt-btif ( 1985): BTA_JvDeleteRecord
I/bt-btif ( 1985): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stop: Stopping peer discovery...
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothLeScanner( 5327): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): stop: Stopping services
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: NOT_STARTED
D/LGWifiP2pService(  904): remove client information from framework
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local services cleared successfully
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5327): Service requests cleared successfully
I/jxcore-log( 5327): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 5327): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565159.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565159.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5327): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: OK
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5327): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565159.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): createAdvertiseData: From: 1454063565159.5327 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5327): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565159.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): start: {"pi":"F8:95:C7:87:85:54","pn":"1454063565159.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454063565159.5327","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3d8987e4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3d8987e4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState add service
D/LGWifiP2pService(  904): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_WIFI
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565159.5327
I/io.jxcore.node.ConnectionHelper( 5327): start: OK
I/wpa_supplicant( 5472): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  904): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: STARTED
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): P2P-FIND-STOPPED 
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  904): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): discovery change broadcast false
I/jxcore-log( 5327): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 5327): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5327): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): onServerStopped
I/bt-btif ( 1985): BTA_JvDeleteRecord
I/bt-btif ( 1985): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothLeScanner( 5327): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139298 a,rg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: No more listeners, de-initializing...
D/LGWifiP2pService(  904): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local services cleared successfully
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5327): Service requests cleared successfully
I/jxcore-log( 5327): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 5327): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565194.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565194.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5327): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: OK
I/io.jxcore.node.ConnectionHelper( 5327): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565194.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
,D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): createAdvertiseData: From: 1454063565194.5327 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5327): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565194.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): start: {"pi":"F8:95:C7:87:85:54","pn":"1454063565194.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454063565194.5327","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cd27e0a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cd27e0a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState add service
D/LGWifiP2pService(  904): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565194.5327
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: OK
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNN,ING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
D/LGWifiP2pService(  904): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: STARTED
I/jxcore-log( 5327): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 5327): 
I/io.jxcore.node.ConnectionHelper( 5327): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Exiting thread
I/wpa_supplicant( 5472): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): onServerStopped
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): discovery change broadcast false
I/bt-btif ( 1985): BTA_JvDeleteRecord
I/bt-btif ( 1985): BTA_JvRfcommStopServer
,D/BluetoothLeScanner( 5327): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): stop: Stopping services
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: NOT_STARTED
D/LGWifiP2pService(  904): remove client information from framework
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5327): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 5327): 
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service request
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5327): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565228.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565228.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5327): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: OK
I/io.jxcore.node.ConnectionHelper( 5327): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565228.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): createAdvertiseData: From: 1454063565228.5327 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5327): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565228.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): start: {"pi":"F8:95:C7:87:85:54","pn":"1454063565228.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454063565228.5327","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e369e3aa target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e369e3aa target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState add service
D/LGWifiP2pService(  904): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_WIFI
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565228.5327
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5327): start: OK
D/LGWifiP2pService(  904): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryMana,gerStateChanged: RUNNING_BLE_AND_WIFI
I/jxcore-log( 5327): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 5327): 
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 5472): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 5327): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): stop: Stopping Bluetooth...
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: 1 listener(s) left
I/bt-btif ( 1985): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: NOT_STARTED
I/bt-btif ( 1985): BTA_JvRfcommStopServer
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): discovery change broadcast false
D/BluetoothLeScanner( 5327): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): stop: Stopping services
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service
D/LGWifiP2pService(  904): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: NOT_INITIALIZED
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/LGWifiP2pService(  904): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5327): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5327): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 5327): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565264.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.,internal.bluetooth.BluetoothManager( 5327): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565264.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5327): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: OK
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5327): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565264.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): createAdvertiseData: From: 1454063565264.5327 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5327): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565264.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): start: {"pi":"F8:95:C7:87:85:54","pn":"1454063565264.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454063565264.5327","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fbb485aa target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fbb485aa target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState add service
D/LGWifiP2pService(  904): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_WIFI
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5327): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565264.5327
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_BLE_AND_WIFI
I/jxcore-log( 5327): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 5327): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnect,or( 5327): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): shutdown
I/wpa_supplicant( 5472): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): onServerStopped
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
I/bt-btif ( 1985): BTA_JvDeleteRecord
I/bt-btif ( 1985): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  904): discovery change broadcast true
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothLeScanner( 5327): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): stop: Stopping services
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): stop: Stopping P2P device discovery...
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): release: No more listeners, de-initializing...
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5327): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 5327): 
D/LGWifiP2pService(  904): remove client information from framework
D/LGWifiP2pService(  904): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager,( 5327): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/LGWifiP2pService(  904): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5327): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565292.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565292.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5327): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: OK
I/io.jxcore.node.ConnectionHelper( 5327): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565292.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): createAdvertiseData: From: 1454063565292.5327 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5327): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565292.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): start: {"pi":"F8:95:C7:87:85:54","pn":"1454063565292.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454063565292.5327","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@1698c868 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@1698c868 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState add service
D/LGWifiP2pService(  904): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: true
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565292.5327
I/wpa_supplicant( 5472): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5327): start: OK
D/LGWifiP2pService(  904): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): P2P-FIND-STOPPED 
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 5327): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 5327): 
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5327): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: 1 listener(s) left
I/bt-btif ( 1985): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: NOT_STARTED
I/bt-btif ( 1985): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothLeScanner( 5327): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): release: No more listeners, de-initializing...
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5327): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 5327): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565321.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  904): remove client information from framework
D/LGWifiP2pService(  904): InactiveState{ when=-4ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local services cleared successfully
D/LGWifiP2pService(  904): InactiveState{ when=-5ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/LGWifiP2pService(  904): P2pEnabledState{ when=-5ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5327): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565321.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5327): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: OK
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5327): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565321.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): createAdvertiseData: From: 1454063565321.5327 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5327): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565321.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): start: {"pi":"F8:95:C7:87:85:54","pn":"1454063565321.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454063565321.5327","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@817d5d36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@817d5d36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState add service
D/LGWifiP2pService(  904): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565321.5327
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 5327): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 5327): 
,D/LGWifiP2pService(  904): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5327): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): shutdown
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): P2P-FIND-STOPPED 
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): onServerStopped
I/bt-btif ( 1985): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
I/bt-btif ( 1985): BTA_JvRfcommStopServer
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: 1 listener(s) left
D/LGWifiP2pService(  904): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/BluetoothLeScanner( 5327): could not find callback wrapper
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopBlePeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
I/or,g.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: NOT_INITIALIZED
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: No more listeners, de-initializing...
D/LGWifiP2pService(  904): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local services cleared successfully
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5327): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 5327): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5327): Service requests cleared successfully
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 5327): 
,I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 4
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565944.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565944.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5327): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
,I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: OK
I/io.jxcore.node.ConnectionHelper( 5327): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565944.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): createAdvertiseData: From: 1454063565944.5327 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5327): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063565944.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): start: {"pi":"F8:95:C7:87:85:54","pn":"1454063565944.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454063565944.5327","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@59b8f9e0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@59b8f9e0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState add service
D/LGWifiP2pService(  904): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Waiting for incoming connections...
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): discovery change broadcast true
,I/wpa_supplicant( 5472): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1806): Event [CTRL-EVENT-SCAN-STARTED ]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063565944.5327
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): P2P-FIND-STOPPED 
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/LGWifiP2pService(  904): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5327): start: OK
I/jxcore-log( 5327): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 5327): 
I/io.jxcore.node.ConnectionHelper( 5327): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal,.bluetooth.BluetoothServerThread( 5327): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): onServerStopped
,I/bt-btif ( 1985): BTA_JvDeleteRecord
I/bt-btif ( 1985): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stop: Stopping peer discovery...
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothLeScanner( 5327): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): stop: Stopping services
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service
D/LGWifiP2pService(  904): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: NOT_INITIALIZED
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5327): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5327): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063566376.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063566376.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5327): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
,I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: OK
I/io.jxcore.node.ConnectionHelper( 5327): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063566376.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
,D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): createAdvertiseData: From: 1454063566376.5327 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5327): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063566376.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): start: {"pi":"F8:95:C7:87:85:54","pn":"1454063566376.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454063566376.5327","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Waiting for incoming connections...
,D/LGWifiP2pService(  904): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@44e966e0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@44e966e0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState add service
D/LGWifiP2pService(  904): add a new client
I/art     (  904): Explicit concurrent mark sweep GC freed 62511(3MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 3.715ms total 227.058ms
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063566376.5327
I/io.jxcore.node.ConnectionHelper( 5327): start: OK
I/jxcore-log( 5327): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 5327): 
I/io.jxcore.node.ConnectionHelper( 5327): connect: Trying to connect to peer with ID foobar
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/LGWifiP2pService(  904): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): P2P-FIND-STOPPED 
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,W/io.jxcore.node.ConnectionHelper( 5327): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 5327): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 5327): ok 78 Should not connect to a bad peer
I/jxcore-log( 5327): 
I/io.jxcore.node.ConnectionHelper( 5327): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): onServerStopped
I/bt-btif ( 1985): BTA_JvDeleteRecord
I/bt-btif ( 1985): BTA_JvRfcommStopServer
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stop: Stopping peer discovery...
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothLeScanner( 5327): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): stop: Stopping services
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service
D/LGWifiP2pService(  904): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: NOT_INITIALIZED
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5327): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5327): ok 79 Should be able to call stopBroadcasting without error
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 4
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063566965.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063566965.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5327): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): start: OK
I/io.jxcore.node.ConnectionHelper( 5327): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063566965.5327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): bind: Binding a new listener
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Waiting for incoming connections...
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): createAdvertiseData: From: 1454063566965.5327 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5327): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5327): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5327): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5327): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454063566965.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): start: {"pi":"F8:95:C7:87:85:54","pn":"1454063566965.5327","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454063566965.5327","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ce370958 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ce370958 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState add service
D/LGWifiP2pService(  904): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 5327): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454063566965.5327
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
I/jxcore-log( 5327): ok 80 Should be able to call startBroadcasting without error
I/jxcore-log( 5327): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/io.jxcore.node.ConnectionHelper( 5327): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
,E/io.jxcore.node.ConnectionHelper( 5327): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 5327): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 5327): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: STARTED
D/LGWifiP2pService(  904): discovery change broadcast true,
I/jxcore-log( 5327): ok 81 Disconnect should fail to a non-existant peer 
I/jxcore-log( 5327): 
I/wpa_supplicant( 5472): p2p0: CTRL-EVENT-SCAN-STARTED 
I/io.jxcore.node.ConnectionHelper( 5327): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): shutdown
D/WfdsMonitor( 1806): Event [CTRL-EVENT-SCAN-STARTED ]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5327): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5327): onServerStopped
I/bt-btif ( 1985): BTA_JvDeleteRecord
I/bt-btif ( 1985): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5472): P2P-FIND-STOPPED 
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5327): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5327): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothLeScanner( 5327): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5327): stop: Stopping services
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5327): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5327): release: No more listeners, de-initializing...
D/LGWifiP2pService(  904): remove client information from framework
D/LGWifiP2pService(  904): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5327): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5327): setState: NOT_STARTED
D/LGWifiP2pService(  904): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState clear service request
I/io.jxcore.node.ConnectionHelper( 5327): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5327): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5327): Service requests cleared successfully
I/jxcore-log( 5327): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 83 host address should match
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 84 port should match
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 85 peer should be available
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 86 peer should be unavailable
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 87 when receiving the first byebye, the second USN should not be set yet
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 88 USN should have changed from the first one
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 89 when receiving the second byebye, the first USN should be already set
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # messages with invalid location or USN should be ignored
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 90 should not have emitted with invalid port
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): WARN thaliWifiInfrastructure Received an invalid USN value: 
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 91 should not have emitted with invalid USN
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 4
,I/jxcore-log( 5327): ok 92 irrelevant messages should be ignored
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 93 relevant messages should not be ignored
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 94 messages from this device should be ignored
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # #start should fail if called twice in a row
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 95 specific error should be received
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,E/jxcore-log( 5327): ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
E/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 96 specific error should be received
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #startUpdateAdvertisingAndListening should fail if router server starting fails
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,E/jxcore-log( 5327): ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
E/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 97 specific error expected
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,D/libc-netbsd( 5327): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5327): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=0; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 10316
D/DnsProxyListener(  281): App 10316 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=0; ai_family=0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/jxcore-log( 5327): ok 98 server should respond with code 200
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #stop can be called multiple times in a row
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 99 should be in stopped state
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 100 should still be in stopped state
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #startListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 101 should be in listening state
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 102 should still be in listening state
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #stopListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 103 should not be in listening state
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ok 104 should still not be in listening state
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # #stopAdvertisingAndListening can be called multiple times in a row
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 105 should not be in advertising state
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 106 should still not be in advertising state
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # setup
I/jxcore-log( 5327): 
I/jxcore-log( 5327): # functions are run from a queue in the right order
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): # teardown
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): ok 107 call order must match
I/jxcore-log( 5327): 
,I/jxcore-log( 5327): Tests Complete
I/jxcore-log( 5327): 
I/jxcore-log( 5327): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 5327): 
,I/chromium( 5327): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 5327): Toggling radios to false
I/jxcore-log( 5327): 
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  904): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3fcfa634 mBinding = false
,D/LocationManagerService(  904): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  904): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  904): JNI:system_update. Event-4
D/BluetoothManagerService(  904): Message: 2
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothManagerService(  904): Sending off request.
D/WifiServiceImplEx(  904): setWifiEnabled: false pid=5327, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  904): setWifiEnabled: false pid=5327, uid=10316
,I/chromium( 5327): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
D/BluetoothAdapterService(164330702)( 1985): disable() called...
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterState( 1985): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 1985): Setting state to 13
I/BluetoothAdapterState( 1985): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(164330702)( 1985): updateAdapterState() - Broadcasting state to 1 receivers.
D/LocationManagerService(  904): getAllProviders()=[passive, gps, network]
,D/Ulp_jni (  904): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  904): JNI:system_update. Event-4
D/BluetoothAdapterProperties( 1985): onBluetoothDisable()
I/BluetoothAdapterState( 1985): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/bt-btif ( 1985): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1985): Scan Mode:20
D/BluetoothAdapterState( 1985): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 1985): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 1985): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/bt-btif ( 1985): btsock_ctrl_hci_cleanup(L202): poll handle:4
I/bt-btif ( 1985): BTA_JvDeleteRecord
I/bt-btif ( 1985): BTA_JvRfcommStopServer
I/bt-btif ( 1985): BTA_JvDeleteRecord
I/bt-btif ( 1985): BTA_JvRfcommStopServer
W/bt-btif ( 1985): invalid rfc slot id: 1
W/bt-btif ( 1985): invalid rfc slot id: 2
D/IOP_DB_BT( 1985): db_close: nbr users 0
D/IOP_DB_BT( 1985): db_close: free database
D/btif_config_util( 1985): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1985): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/btif_config_util( 1985): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 1985): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 1985): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 1985): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 1985): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:G3s-1
D/btif_config_util( 1985): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 1985): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 1985): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 1985): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 1985): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 1985): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 1985): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 1985): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 1985): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 1985): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 1985): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 1985): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 1985): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 1985): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 1985): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 1985): enum_config(L344): out, value:x
D/btif_config_util( 1985): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 1985): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 1985): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 1985): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 1985): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 1985): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 1985): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:9,3,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 1985): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 1985): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 1985): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 1985): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 1985): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 1985): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 1985): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 1985): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 1985): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 1985): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:�
D/btif_config_util( 1985): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string,
D/btif_config_util( 1985): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 1985): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
,D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
,D/btif_config_util( 1985): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer,
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:$
D/btif_config_util( 1985): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 1985): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int,
,D/btif_config_util( 1985): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int,
D/btif_config_util( 1985): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust,
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
,D/btif_config_util( 1985): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service,
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
,D/btif_config_util( 1985): enum_config(L344): out, value:,
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
,D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer,
,D/btif_config_util( 1985): enum_config(L344): out, value:�
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:A5-1
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass,
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int,
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass,
D/btif_config_util( 1985): enum_config(L344): out, value:Z
,D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType,
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks,
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust,
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int,
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
,D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1985): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:#
D/btif_config_util( 1985): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string,
D/btif_config_util( 1985): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 1985): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1985): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:�
D/btif_config_util( 1985): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
,D/btif_config_util( 1985): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:XT1072
D/btif_config_util( 1985): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
E/bt-btif ( 1985): btif_hf_upstreams_evt: wrong handle = 18022 
W/bt-obex ( 1985): Ignore event 10 in state 1
,I/bt-btif ( 1985): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1985): ops_state_cb(L223):  ops_state_cb state:3
D/OppService( 1985): onOpsStateChange() :3
D/OppService( 1985): Recieved MESSAGE_OPS_DISABLE
W/bt-obex ( 1985): Ignore event 10 in state 1
E/bt-btif ( 1985): bta_gattc_deregister Deregister Failedm unknown client cif
E/WifiStateMachine(  904): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  904): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log( 5327): Radios toggled
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ****TEST TOOK:  ms ****
I/jxcore-log( 5327): 
I/jxcore-log( 5327): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5327): 
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothManagerService(  904): Message: 60
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
,D/btif_config_util( 1985): enum_config(L344): out, value:a
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:S5-1
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1985): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:	a
D/btif_config_util( 1985): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:G4-1
D/btif_config_util( 1985): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1985): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:a
D/btif_config_util( 1985): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:Thali Test (Galaxy S5)
D/btif_config_util( 1985): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 1985): enum_config(L30,2): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
V/BluetoothPbapService( 1985): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothManagerService(  904): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  904): Bluetooth State Change Intent: 12 -> 13
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:�
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:Thali Test (Galaxy A5)
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust,
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:�
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
,D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
,D/btif_config_util( 1985): enum_config(L344): out, value:A
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:Thali Test's G2
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/LGWifiP2pService(  904): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothMapMasInstance( 1985): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 1985): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 1985): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 1985): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 1985): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 1985): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 1985): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 1985): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:,
,D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:	a
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:Note3-1
,D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:�
,D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:A3-1
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1985): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:�
D/btif_config_util( 1985): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name,
D/btif_config_util( 1985): enum_config(L344): out, value:XT1039
D/btif_config_util( 1985): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevClass,
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevClass, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
,D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
,D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpVer, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:	a
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Name
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
,D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
,D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1985): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:�,
,D/btif_config_util( 1985): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:HTC One_M8
D/btif_config_util( 1985): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
,D/btif_config_util( 1985): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
,D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1985): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/LGBluetoothAPIService( 1806): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/btif_config_util( 1985): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:GlobalTrust
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:"
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:Note4-1
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Service
,D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1985): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/CommandListener(  281): Clearing all IP addresses on wlan0
D/btif_config_util( 1985): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:�
D/btif_config_util( 1985): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 1985): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevType
D/DhcpStateMachine(  904): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:GlobalTrust, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 1985): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Manufacturer, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpVer, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:�
D/btif_config_util( 1985): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Name
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:G3-1
D/btif_config_util( 1985): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevType
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Service
,D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpVer, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:	a
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Name
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevType
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:JustWorks, value type:int
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 7
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:GlobalTrust
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1985): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Manufacturer
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpSubVer
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:�
D/btif_config_util( 1985): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 1985): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:GlobalTrust
,D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 1985): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Manufacturer, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpSubVer
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:A
D/btif_config_util( 1985): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:S5mini-1
D/btif_config_util( 1985): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevClass, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
D/btif_config_util( 1985): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Service, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 1985): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1985): enum_config(L300): in, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:T\���K�`�D�`�D�
,D/btif_config_util( 1985): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:���
D/btif_config_util( 1985): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevType
,D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 1985): enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
,D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpVer, value type:int
,D/btif_config_util( 1985): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpSubVer, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 1985): enum_config(L344): out, value:�
D/btif_config_util( 1985): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Name
,D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:A3-1
D/btif_config_util( 1985): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:Z
,D/btif_config_util( 1985): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:JustWorks, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:GlobalTrust, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:00:00:00:67:53, value:DevClass
,D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:$��
,D/btif_config_util( 1985): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:`��
D/btif_config_util( 1985): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevType
,D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:���
D/btif_config_util( 1985): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
,D/btif_config_util( 1985): enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:�_
D/btif_config_util( 1985): enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:00:00:00:00:41:9e, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:00:00:00:00:41:9e, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:4g�
D/btif_config_util( 1985): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:��f
D/btif_config_util( 1985): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/btif_config_util( 1985): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:Name, value type:string
D/btif_config_util( 1985): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 1985): enum_config(L344): out, value:4g�������v��
D/btif_config_util( 1985): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevClass, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 1985): enum_config(L344): out, value:��\
D/btif_config_util( 1985): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevType
D/btif_config_util( 1985): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevType, value type:int
D/btif_config_util( 1985): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevType
D/btif_config_util( 1985): enum_config(L344): out, value:
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1733): Read error: ssl=0xaaedb200: I/O error during system call, Connection timed out
V/NativeCrypto( 1733): SSL shutdown failed: ssl=0xaaedb200: I/O error during system call, Broken pipe
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
,D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/ConnectivityService(  904): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  904): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/BluetoothMapService( 1985): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1985): STATE_TURNING_OFF
V/BluetoothMapService( 1985): Handler(): got msg=4
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/BluetoothMapService( 1985): MAP Service closeService in
I/[SystemUI]BluetoothHandler( 1373): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
D/BluetoothMapMasInstance( 1985): MAP Service shutdown
D/LGBluetoothMapAdapter( 1985): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1985): MAP Service closeService out
,I/jxcore-log( 5327): Toggling radios to false
I/jxcore-log( 5327): 
I/ActivityManager(  904): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7108 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  904): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3fcfa634 mBinding = false
,D/BluetoothManagerService(  904): Message: 2
,D/BluetoothManagerService(  904): Sending off request.
D/ConnectivityService(  904): Default network via Wi-Fi disconnect. stop DSQN
D/WifiHS20(  904): hidePasspointNotification off =false
D/DSQN    (  904): disableDataServiceNotify
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DSQN    (  904): stop dsqn bin
D/WifiHS20(  904): hidePasspointNotification off =false
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNetworkAgent(  904): NetworkAgent: NetworkAgent channel lost
D/LGWifiP2pService(  904): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): P2pDisablingState
D/LGWifiP2pService(  904): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): p2p socket connection lost
D/LGWifiP2pService(  904): P2pDisabledState
D/WifiScanningService(  904): SCAN_AVAILABLE : 1
D/RttService(  904): SCAN_AVAILABLE : 1
D/ConnectivityService(  904): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiScanningService(  904): DefaultState got{ when=-4ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  904): EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  904): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  904): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker(  904): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  904): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  904): Disconnected - quitting
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  904): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  904): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  904): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  904): Removing idletimer
W/Settings(  904): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiServiceImplEx(  904): setWifiEnabled: false pid=5327, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  904): setWifiEnabled: false pid=5327, uid=10316
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/ConnectivityService(  904): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/LGWifiP2pService(  904): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  904): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1806): WifiP2pState is changed : false
D/WfdsService( 1806): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsJNI ( 1806): doCommand: P2P_STOP_FIND
D/TelephonyNetworkFactory-1( 1743): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/jxcore-log( 5327): Radios toggled
I/jxcore-log( 5327): 
,D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524292
D/BluetoothAdapterService(164330702)( 1985): disable() called...
D/ConnectivityManager.CallbackHandler( 4023): CM callback handler got msg 524292
D/TelephonyNetworkFactory-1( 1743):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WfdsService( 1806): Set the WFDS Monitor: false
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/CommandListener(  281): Clearing all IP addresses on wlan0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:32:49.642 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:32:49.644 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothAdapterService( 1985): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService(  904): IBluetooth.disable() returned false
D/Tethering(  904): MasterInitialState.processMessage what=3
D/Tethering(  904): MasterInitialState.processMessage what=3
,D/WfdsMonitor( 1806): WFDS Monitor is stopped
D/CtrlSupplicant( 1806): Received on exit socket, terminate
E/CtrlSupplicant( 1806): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1806): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1806): WfdsMonitorThread is received the interrupt - closing
D/WfdsService( 1806): STATE : WfdsDisabledState - enter
D/WfdsService( 1806): WFDS: Scanner is paused
D/WfdsDiscoveryStore( 1806): Clear Discovery Method Map: ScanAlwaysMode false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
W/WfdsSession:Controller( 1806): DefaultState - msg [9441355] is not handled
W/QCNEJ   ( 1842): |CORE| No family connected
W/QCNEJ   ( 1842): |CORE| No family connected
I/QCNEJ   ( 1842): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1842): |CORE| sendDefaultNwMsg: default = -1
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WifiHS20(  904): hidePasspointNotification off =false
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:32:49.667 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  904): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  904): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  904): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WIFI    (  904): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  904):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:32:49.67 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  904): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt(  904): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  904): setSupplicantStateDISCONNECTED
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.WIFI_STATE_CHANGED at null
,I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 5
I/wpa_supplicant( 5472): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 5472): monitor socket send errors count : 1
I/wpa_supplicant( 5472): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1806-2\x00 that cannot receive messages
I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 10
I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 7
D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  904): StoppedState
D/DhcpStateMachine(  904): StoppedState{ when=-100ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5472): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 5472): USIM:  scard_deinit function
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
,D/libc-netbsd(  904): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  904): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 5
I/wpa_supplicant( 5472): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  904): InitialState.processMessage what=4
D/WfdsService( 1806): Supplicant Connection state is changed : false
D/Tethering(  904): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiOffDelayIfNotUsed(  904): stopMonitoring
D/WfdsService( 1806): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1806): Set the WFDS Monitor: false
D/WfdsMonitor( 1806): WFDS Monitor is stopped
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 11:32:49.879 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  904): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt(  904): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt(  904): batteryPsActivateMsgHandler : this is not treated
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.WIFI_STATE_CHANGED at null
W/Settings( 1733): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AndroidRuntime( 7100): 
D/AndroidRuntime( 7100): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/ResourcesManager( 7108): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7108): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7108): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7108): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7108): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/AndroidRuntime( 7100): CheckJNI is OFF
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
D/WifiController(  904): battery changed pluggedType: 2
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
I/IndexDatabaseHelper( 7108): Using schema version: 115
,I/IndexDatabaseHelper( 7108): Index is fine
I/ActivityManager(  904): Process com.android.contacts (pid 6820) has died
,W/ContextImpl( 7108): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,W/bt_userial( 1985): select_read return size <=0:0, exiting userial_read_thread
,D/bt_hwcfg( 1985): hw_epilog_process
W/bt-l2cap( 1985): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1985): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1985): ag scb idx 1 not allocated
E/bt-btif ( 1985): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1985): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1985): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1985): ag scb idx 1 not allocated
E/bt-btif ( 1985): BTA AG is already disabled, ignoring ...
E/bt-btif ( 1985): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 1985): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_userial_vendor( 1985): device fd = 67 close
I/ActivityManager(  904): Process com.android.gallery3d (pid 6797) has died
V/BluetoothPbapReceiver( 1985): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1985): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1985): ***********state = 13
E/bt_vendor( 1985): [BTUI] Proto is enabled. Set Proto disable!!
,V/BluetoothPbapReceiver( 1985): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 1985): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1985): state: 13
V/BluetoothPbapService( 1985): Pbap Service closeService in
D/AndroidRuntime( 7100): Calling main entry com.android.commands.pm.Pm
V/BluetoothPbapService( 1985): successfully stopped pbap service
V/BluetoothPbapService( 1985): Pbap Service closeService out
V/BluetoothPbapService( 1985): Pbap Service onDestroy
V/BluetoothPbapService( 1985): Pbap Service closeService in
V/BluetoothPbapService( 1985): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 1985): [BTUI] cleanup
V/WiFiOffLoadBroadcast( 7108): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  904): Killing 5327:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,D/WiFiOffLoadBroadcast( 7108): MCCMNC not supported: null
,D/BluetoothManagerService(  904): Message: 20
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a46daa3:true
,I/WindowState(  904): WIN DEATH: Window{111b502c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  904): Focus left window: Window{111b502c u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  904): Window went away: Window{111b502c u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  904): Skipping PackageSetting{3e7db044 com.example.hello/10317} due to missing metadata
I/GKI_LINUX( 1985): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,I/ActivityManager(  904):   Force finishing activity ActivityRecord{2662f559 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  904): Display changed displayId=0
D/DSDPConnection( 1743): Display #0 changed.
W/ActivityManager(  904): Spurious death for ProcessRecord{35627dff 5327:com.test.thalitest/u0a316}, curProc for 5327: null
,D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
I/GKI_LINUX( 1985): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1985): GKI_destroy_task(): task [BTU] terminated
I/bt-btif ( 1985): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 1985): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BluetoothManagerService(  904): Message: 30
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
D/BtSettings.ProfileConfig( 1985): Unable to read settings
D/BtSettings.ProfileConfig( 1985): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1985): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1985): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1985): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1985): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1985): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 1985): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 1985): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1985): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1985): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1985): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1985): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
,D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
,D/HeadsetService( 1985): Received stop request...Stopping profile...
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1880): [Launcher.java:5203:onStart()]onStart
,W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
D/BluetoothManagerService(  904): Message: 30
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
I/LGBluetoothHfpAdapter( 1985): [BTUI] LGBluetoothHfpAdapter cleanup
D/HeadsetStateMachine( 1985): Exit Disconnected: -1
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
,W/BluetoothAdapterService( 1985): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
W/LGBluetoothHeadsetServiceJni( 1985): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1985): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1985): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1985): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_REMOVED
D/BluetoothAdapterState( 1985): Stopping profile services that were post enabled
,W/System.err( 3391): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3391): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3391): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3391): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3391): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3391): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3391): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3391): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3391): 	at java.lang.reflect.Method.invoke(Native Method)
D/A2dpService( 1985): Received stop request...Stopping profile...
W/System.err( 3391): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3391): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3391): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/A2dpStateMachine( 1985): Exit Disconnected: -1
,D/LocalBluetoothProfileManager( 7108): Adding local MAP profile
I/[LGHome]EVENT( 1880): [Launcher.java:776:onResume()]onResume
D/BluetoothMap( 7108): Create BluetoothMap proxy object
D/BluetoothManagerService(  904): Message: 30
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
D/BluetoothHeadset( 1743): Proxy object disconnected
D/BluetoothHeadset( 1743): Proxy object disconnected
D/BluetoothHeadset( 1743): Proxy object disconnected
D/LGBluetoothA2dpAdapter( 1985): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 1985): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 1985): [BTUI] terminate
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
D/BluetoothManagerService(  904): Message: 30
D/BluetoothManagerService(  904): Message: 31
D/HidService( 1985): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
,I/art     ( 1936): Explicit concurrent mark sweep GC freed 24329(1411KB) AllocSpace objects, 5(142KB) LOS objects, 40% free, 12MB/21MB, paused 2.438ms total 126.601ms
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/HealthService( 1985): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
I/InputReader(  904): Reconfiguring input devices.  changes=0x00000010
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1985): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/PanService( 1985): Received stop request...Stopping profile...
I/[LGHome]LGActivityUtil( 1880): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
D/HeadsetStateMachine( 1985): Unbinding service...
I/[LGHome]EVENT( 1880): [Launcher.java:929:onResume()]onResume end
I/Activity( 1880): Activity.onPostResume() called 
D/HeadsetPhoneState( 1985): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1985): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 1985): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1985): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 1985): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1985): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 1985): [BTUI] LGBluetoothHfpAdapter cleanup
D/BtGatt.DebugUtils( 1985): handleDebugAction() action=null
D/BtGatt.GattService( 1985): Received stop request...Stopping profile...
D/BtGatt.GattService( 1985): stop()
D/BtGatt.AdvertiseManager( 1985): advertise clients cleared
,D/LGBluetoothGattAdapter( 1985): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
D/BluetoothMapService( 1985): Received stop request...Stopping profile...
D/BluetoothMapService( 1985): stop()
D/BluetoothMapEmailAppObserver( 1985): deinitObservers()
D/BluetoothMapEmailAppObserver( 1985): removeReceiver()
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
D/SapService( 1985): Received stop request...Stopping profile...
D/SapService( 1985): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 1985): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 1985): [BTUI] terminateSapManager
D/LgeBluetoothSimManager( 1743): [BTUI] SAP_DISABLE_EVT
,D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/**BluetoothFTPService( 1985): Received stop request...Stopping profile...
D/**BluetoothFTPService( 1985): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 1985): closeFtpServerNative
I/art     ( 4023): Explicit concurrent mark sweep GC freed 22060(1250KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 14MB/19MB, paused 1.441ms total 182.891ms
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
D/LocalBluetoothProfileManager( 7108): LocalBluetoothProfileManager construction complete
D/**OppService( 1985): Received stop request...Stopping profile...
D/OppService( 1985): Stopping Bluetooth OppService
D/OppService( 1985): cleanup OPP Service
W/BluetoothOPPServiceJni( 1985): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 1985): Cleaning up Bluetooth OPP callback object
D/OppService( 1985): remove callbacks and handler
D/LGBluetoothOppAdapter( 1985): [BTUI] LGBluetoothOppAdapter cleanup
D/LGBluetoothFeatureConfig( 7108):  get() - isFeatureLoaded : false
D/OppService( 1985): cleanup done
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9cb7cce
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
,D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1985): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1985): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/BluetoothA2dpServiceJni( 1985): cleanupNative
I/GKI_LINUX( 1985): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1985): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1985): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1985): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHidServiceJni( 1985): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 1985): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 1985): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1985): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 1985): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.andro,id.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1985): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 1985): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1985): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1985): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1985): Handler(): got msg=4
D/BluetoothMapService( 1985): MAP Service closeService in
D/LGBluetoothMapAdapter( 1985): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1985): MAP Service closeService out
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1985): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 1985): cleanup()
D/BluetoothMapService( 1985): MAP Service closeService in
D/LGBluetoothMapAdapter( 1985): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1985): MAP Service closeService out
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
,D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1985): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 1985): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 1985): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
,D/BluetoothAdapterService( 1985): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothFTPService( 1985): cleanup FTP Service
V/BluetoothFTPServiceJni( 1985): closeFtpServerNative
V/BluetoothFTPServiceJni( 1985): cleanupNative
W/BluetoothFTPServiceJni( 1985): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 1985): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 1985): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 1985): cleanup done
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(164330702)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
,D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(164330702)( 1985): onProfileServiceStateChange() - All profile services stopped...
D/OppService( 1985): cleanup OPP Service
D/OppService( 1985): remove callbacks and handler
D/LGBluetoothOppAdapter( 1985): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 1985): cleanup done
D/BluetoothAdapterState( 1985): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1985): Setting state to 10
I/BluetoothAdapterState( 1985): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(164330702)( 1985): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  904): Message: 60
D/BluetoothManagerService(  904): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  904): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 1985): Entering OffState
D/BluetoothA2dp(  904): onBluetoothStateChange: up=false
,D/BluetoothPan( 7108): onBluetoothStateChange on: false
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
D/BluetoothPbap( 7108): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1743): onBluetoothStateChange: up=false
D/BluetoothHeadset(  904): onBluetoothStateChange: up=false
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
D/BluetoothInputDevice( 7108): onBluetoothStateChange: up=false
D/BluetoothMap( 7108): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1743): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1743): onBluetoothStateChange: up=false
,D/BluetoothAdapterService(164330702)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f1be594
D/BluetoothManagerService(  904): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  904): Broadcasting onBluetoothServiceDown() to 8 receivers.
W/ResourcesManager( 1373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1373): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/[LGHome]LGWallpaperInfo( 1880): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1880): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/BluetoothManagerService(  904): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  904): Broadcasting onQBluetoothServiceDown() to 0 receivers.
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
D/BluetoothManagerService(  904): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3fcfa634 mBinding = false
D/BluetoothManagerService(  904): Sending unbind request.
D/BluetoothManagerService(  904): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService(164330702)( 1985): onUnbind() - calling cleanup
,D/BluetoothAdapterService(164330702)( 1985): cleanup()
D/LGBluetoothAPIService( 1806): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1806): Message: 2
D/BluetoothAdapter( 1373): 1059134690: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1373): 1059134690: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothAPIService( 1806): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2e9a9ed5 mBinding = false
D/LGBluetoothAPIService( 1806): Sending unbind request.
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1373): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
I/SystemUI[Framework](  904): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/BluetoothAdapterService(164330702)( 1985): cleanup() - Cleaning up adapter native
W/PhoneWindowManagerEx(  904): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  904): setLGSystemUiVisibility(0x0)
I/bt-btif ( 1985): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 1985): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
D/StatusBarManagerServiceEx(  904): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/bt-btif ( 1985): HAL bt_hal_cbacks->thread_evt_cb
I/SystemUI[Framework](  904): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a5ea9cc,  pkg=WindowManager.LayoutParams
,I/SystemUI[Framework](  904): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  904): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
I/GKI_LINUX( 1985): gki_task task_id=1 [BTIF] terminating
W/PhoneWindowManagerEx(  904): Call!!!getLGSystemUiVisibility. =0x0
I/GKI_LINUX( 1985): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 1985): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1985): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1985): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1985): GKI_exit_task 2 done
I/GKI_LINUX( 1985): GKI_exit_task 1 done
I/GKI_LINUX( 1985): GKI_exit_task 0 done
I/BluetoothServiceJni( 1985): cleanupNative: return from cleanup
D/StatusBarManagerServiceEx(  904): setLGSystemUiVisibility(0x0)
W/LGBluetoothServiceJni( 1985): Cleaning up Bluetooth Service callback object
D/StatusBarManagerServiceEx(  904): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  904): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a5ea9cc,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  904): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LGBluetoothSettingsDBObserver( 1985): [BTUI] unregister observer for LG device name DB
D/InputDispatcher(  904): Focus entered window: Window{34423f0d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/BluetoothAdapterService(164330702)( 1985): cleanup() - Bluetooth process exited normally.
D/BluetoothAdapterService(164330702)( 1985): cleanup() done
I/art     ( 1985): System.exit called, status: 0
I/AndroidRuntime( 1985): VM exiting with result code 0, cleanup skipped.
W/ResourcesManager( 1373): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
,V/AudioFlinger(  286): 1985 died, releasing its sessions
V/AudioFlinger(  286):  pid 1743 @ 0
V/AudioFlinger(  286):  pid 3113 @ 1
V/AudioFlinger(  286):  pid 3113 @ 2
D/FMFRW_FmProxy( 1806): Fm Proxy object disconnected
D/BluetoothAdapter( 1733): 585569653: getState() :  mService = null. Returning STATE_OFF
I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
D/BluetoothAdapter( 1733): 585569653: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothUserBindClient( 7108): [BTUI] initUserBindClient
W/ContextImpl( 7108): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1880): [setNavigationBarColor] color=0x 0
W/ResourcesManager( 1373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1373): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1373): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
D/administrator(  904): Handling package changes for user 0
,I/ActivityManager(  904): Process com.android.bluetooth (pid 1985) has died
W/ActivityManager(  904): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 1000ms
,I/ActivityManager(  904): Start proc com.android.bluetooth for service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer: pid=7157 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
D/KeyguardModel( 1373): handleShortcutListChanged...
,D/DockEventReceiver( 7108): finishStartingService: stopping service
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
,D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
W/InputMethodManagerService(  904): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  904): Got RemoteException sending setActive(false) notification to pid 5327 uid 10316
D/KeyguardModel( 1373): handleShortcutListChanged...
,W/ResourcesManager( 7157): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7157): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7157): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 7157): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
D/LGBluetoothAuthorization( 7108): [BTUI] cancel All Notification
I/NotificationManager( 7108): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 7108): com.android.settings: cancel(-1000001) by com.android.settings
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/NotificationManager( 7108): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 7108): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 7108): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 7108): com.android.settings: cancel(-1000041) by com.android.settings
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/BluetoothAdapterApp( 7157): Loading JNI Library
,I/ActivityManager(  904): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7178 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/art     (  904): Explicit concurrent mark sweep GC freed 35095(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 20.123ms total 453.117ms
E/BluetoothServiceJni( 7157): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
,D/BluetoothAdapterApp( 7157): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@b8d2d91 Instance Count = 1
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/NotificationService(  904): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  904): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/BluetoothPermissionRequest( 7108): onReceive
,I/Timeline(  904): Timeline: Activity_windows_visible id: ActivityRecord{1cbe4c69 u0 com.lge.launcher2/.Launcher t221} time:308828
D/JobSchedulerService(  904): Receieved: android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAuthorization( 7108): [BTUI] cancel All Notification
I/NotificationManager( 7108): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 7108): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 7108): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 7108): com.android.settings: cancel(-1000021) by com.android.settings
D/BluetoothAdapterApp( 7157): onCreate
I/NotificationManager( 7108): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 7108): com.android.settings: cancel(-1000041) by com.android.settings
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/TaskPersister(  904): removeObsoleteFile: deleting file=222_task.xml
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/LGBluetoothServiceJni( 7157): classInitNative: succeeds
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/BtSettings.ProfileConfig( 7157): [BTUI] HeadsetServiceis supported
D/BtSettings.ProfileConfig( 7157): Adding HeadsetService
,D/BtSettings.ProfileConfig( 7157): [BTUI] A2dpServiceis supported
D/BtSettings.ProfileConfig( 7157): Adding A2dpService
D/BtSettings.ProfileConfig( 7157): [BTUI] HidServiceis supported
D/BtSettings.ProfileConfig( 7157): Adding HidService
D/BtSettings.ProfileConfig( 7157): [BTUI] HealthServiceis supported
D/BtSettings.ProfileConfig( 7157): Adding HealthService
D/LGBluetoothFeatureConfig( 7157): isSupportPan() :  mTargetOp=OPEN
D/LGBluetoothFeatureConfig( 7157): isSupportPan() :  mTargetOp=OPEN
D/BtSettings.ProfileConfig( 7157): [BTUI] PanServiceis supported
D/BtSettings.ProfileConfig( 7157): Adding PanService
D/BtSettings.ProfileConfig( 7157): [BTUI] GattServiceis supported
,D/BtSettings.ProfileConfig( 7157): Adding GattService
D/BtSettings.ProfileConfig( 7157): [BTUI] BluetoothMapServiceis supported
D/BtSettings.ProfileConfig( 7157): Adding BluetoothMapService
V/LGBluetoothServiceAdapter( 7157): [BTUI] region:EU country:EU
D/BtSettings.ProfileConfig( 7157): [BTUI] SapServiceis supported
D/BtSettings.ProfileConfig( 7157): Adding SapService
D/BtSettings.ProfileConfig( 7157): [BTUI] FTPServiceis supported
D/BtSettings.ProfileConfig( 7157): Adding FTPService
E/BtSettings.ProfileConfig( 7157): [BTUI] HeadsetClientServiceis NOT supported
D/BtSettings.ProfileConfig( 7157): [BTUI] OppServiceis supported
D/BtSettings.ProfileConfig( 7157): Adding OppService
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1880): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/BtSettings.ProfileConfig( 7157): deviceMode from shared preference   -1
D/BtSettings.ProfileConfig( 7157): checkAndAdjustDeviceModeConfiguration deviceMode1
D/BtSettings.ProfileConfig( 7157): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 7157): Unable to read settings
D/BtSettings.ProfileConfig( 7157): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 7157): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 7157): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 7157): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 7157): 	at com.broadcom.bt.service.ProfileConfig.checkAndAdjustDeviceModeConfiguration(ProfileConfig.java:400)
D/BtSettings.ProfileConfig( 7157): 	at com.broadcom.bt.service.ProfileConfig.init(ProfileConfig.java:550)
D/BtSettings.ProfileConfig( 7157): 	at com.lge.bluetooth.adapter.LGBluetoothProfileConfigAdapter.init(LGBluetoothProfileConfigAdapter.java:30)
D/BtSettings.ProfileConfig( 7157): 	at com.android.bluetooth.btservice.AdapterApp.onCreate(AdapterApp.java:67)
D/BtSettings.ProfileConfig( 7157): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
D/BtSettings.ProfileConfig( 7157): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
D/BtSettings.ProfileConfig( 7157): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
D/BtSettings.ProfileConfig( 7157): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
D/BtSettings.ProfileConfig( 7157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 7157): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 7157): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
D/BtSettings.ProfileConfig( 7157): 	at java.lang.reflect.Method.invoke(Native Method)
D/BtSettings.ProfileConfig( 7157): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BtSettings.ProfileConfig( 7157): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
D/BtSettings.ProfileConfig( 7157): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/BtSettings.ProfileConfig( 7157): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 7157): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 7157): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 7157): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 7157): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 7157): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfi,g( 7157): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 7157): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 7157): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
E/b       ( 1604): Unable to connect to the editor to retrieve text... will retry later
,D/LGBluetoothUserBindClient( 7108): [BTUI] onServiceConnected
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
D/AndroidRuntime( 7100): Shutting down VM
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
I/FmServiceJni( 7157): classInitNative: succeeds
D/FmService( 7157): FmReceiverServiceStub createdcom.broadcom.fm.fmreceiver.FmService$FmReceiverServiceStub@3c611cdservicecom.broadcom.fm.fmreceiver.FmService@6503a82
D/FmNativehandler( 7157): start
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,D/BluetoothRadioManager( 7157): [BTUI] getRadioManager()
D/BluetoothRadioManager( 7157): [BTUI] BluetoothRadioManager()
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/BluetoothManagerService(  904): Message: 20
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31b9f9a:true
,I/PCSuite ( 7178): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/BluetoothRadioManager( 7157): doBind: com.broadcom.bt.service.radiomanager.IBluetoothRadioManager
,V/FmService( 7157): FM Service  onCreate
D/FmService( 7157): Binding service...
D/PCSuite ( 7178): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7178): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/FMFRW_FmProxy( 1806): Fm proxy onServiceConnected() name = ComponentInfo{com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService}, service = android.os.BinderProxy@21f8b6ea
D/LGBluetoothOppAdapter( 7157): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothOppReceiver( 7157): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 7157): [BTUI] cancel opp incoming file confirm notification
I/NotificationManager( 7157): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/BluetoothOppNotification( 7157): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 7157): com.android.bluetooth: cancel(-1) by com.android.bluetooth
I/ActivityManager(  904): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7207 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/BluetoothAdapterService( 7157): Set JNI Library before classInit
,D/BluetoothAdapterService(16717807)( 7157): AdapterService() - REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothAdapterService(16717807)( 7157): onCreate()
D/BluetoothAdapterState( 7157): make
I/bluedroid( 7157): init
I/BluetoothAdapterState( 7157): Entering OffState
,I/bte_conf( 7157): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 7157): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 7157): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 7157): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 7157): [BTUI] lge_load_bluetooth_address
D/bt-btif ( 7157):  [BTUI] Load_abtddress
D/BTIF_CORE( 7157): [BTUI] lge_wait_for_load_bluetooth_address : waiting...
D/lge_bdaddr_loader( 7219): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 7219): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 7219): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 7219): [BTUI] bdaddr to set in property : F8:95:C7:87:85:54
I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager(  904): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType(  904): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,E/lge_bdaddr_loader( 7219): [BTUI] bluetooth_load_bdaddress : OK => F8:95:C7:87:85:54
D/lge_bdaddr_loader( 7219): [BTUI] bdaddr_loader ::: END
W/ResourcesManager( 7207): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BTIF_CORE( 7157): [BTUI] lge_wait_for_load_bluetooth_address : success!
D/bt-btif ( 7157): PERSIST_BDADDR_PROPERTY is  F8:95:C7:87:85:54
D/bt-btif ( 7157): Got prior random BDA F8:95:C7:87:85:54
E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/bluedroid( 7157): get_profile_interface socket
I/GKI_LINUX( 7157): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 7157): get_profile_interface map_client
E/BluetoothServiceJni( 7157): Error getting mapclient interface
D/bt-btif ( 7157): btif task starting
D/bt-btif ( 7157): btif_associate_evt: notify ASSOCIATE_JVM
I/bt-btif ( 7157): btif_get_adapter_property 2
I/bt-btif ( 7157): btif_get_adapter_property 2
I/bt-btif ( 7157): btif_get_adapter_property 1
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/bt-btif ( 7157): execute storage request event : 3
D/bt-btif ( 7157): btif_storage_get_adapter_property property->type:2 
I/bt-btif ( 7157): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 7157): Address is:F8:95:C7:87:85:54
I/bt-btif ( 7157): execute storage request event : 3
D/bt-btif ( 7157): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 7157): in, bd addr:, prop type:1, len:512
I/bt-btif ( 7157): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  904): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  904): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 7157): Name is: G3s-1
D/BluetoothAdapterService( 7157): getAdapterService() - Service not available
D/LGBluetoothServiceAdapter( 7157): [BTUI] check adapter is available - false.
D/LGBluetoothSettingsDBObserver( 7157): [BTUI] register observer for LG device name DB
,D/BluetoothAdapterService(16717807)( 7157): onBind()
,D/BluetoothRadioManager( 7157): onServiceConnected: connected to AdapterService com.android.bluetooth.btservice.AdapterService
D/BluetoothRadioManager( 7157): Message: 40
D/BluetoothRadioManager( 7157): MESSAGE_RADIO_SERVICE_CONNECTED: 1
D/BluetoothRadioManager( 7157):  Turning on BT modules Radio on = false
V/BluetoothSapReceiver( 7157): [BTUI] checkServiceStart
,D/LGBluetoothStateChangeReceiver( 7157): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1880): getTextAfterCursor on inactive InputConnection
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  904): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7230 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
D/BluetoothManagerService(  904): Message: 20
,D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b7dd0ab:true
,D/BluetoothAdapter( 7207): 164330702: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 7207): 164330702: getState() :  mService = null. Returning STATE_OFF
E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 7230): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,V/WiFiOffLoadBroadcast( 7108): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE

```
