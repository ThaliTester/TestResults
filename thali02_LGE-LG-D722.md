#### Test 58135655e794d2c_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/UEI.SmartControl( 4692): Internal timer expired: 4
--------- beginning of system
I/ActivityManager(  973): Killing 5125:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  973): failed to open /acct/uid_10023/pid_5125/cgroup.procs: No such file or directory
,D/AndroidRuntime( 5237): 
D/AndroidRuntime( 5237): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5237): CheckJNI is OFF
D/AndroidRuntime( 5237): Calling main entry com.android.commands.am.Am
I/ActivityManager(  973): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  973): setTaskToReturnTo : TaskRecord{18802fb5 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  973): setTaskToReturnTo : TaskRecord{18802fb5 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  973): AppWindowTokenEx init.. 
D/ContextHelper(  973): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  973): Focus left window: Window{d621bf5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5237): Shutting down VM
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  973): check instance of lgWin Window{15900697 u0 Starting com.test.thalitest}
I/ActivityManager(  973): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5252 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1939): Closing mic
I/MicrophoneInputStream( 1939): mic_close com.google.android.apps.gsa.speech.audio.u@2d7e9232
V/AudioRecord( 1939): stop()
D/AudioRecord( 1939): AudioRecord->stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioFlinger(  283): Record stopped OK
V/AudioPolicyManager(  283): stopInput() input 16
V/AudioPolicyService(  283): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  283): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  283): ThreadBase::setParameters() routing=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3e65000
I/WindowStateAnimator(  973): Starting window displayed
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
I/SystemUI[Framework](  973): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  973): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  973): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  973): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  973): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2c625cd8,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  973): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1375): draw background and invalidate : color = f000000
D/BarTransitions( 1375): draw background and invalidate : color = 14131313
V/audio_hw_primary(  283): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  283): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  283): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  283): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  283): disable_audio_route: exit
E/audio_hw_primary(  283): disable_snd_device: enter 144
D/hardware_info(  283): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  283): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  283): stop_input_stream: exit: status(0)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  283): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  283): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  283): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  283): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  283): setParameters(): io 16, keyvalue hotword_active=0, calling pid 283
V/AudioFlinger(  283): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
,V/AudioFlinger(  283): RecordThread: loop starting
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3e65000
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioPolicyManager(  283): releaseInput() 16
V/AudioPolicyManager(  283): closeInput(16)
V/AudioFlinger(  283): releasing 15 from 1939 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/AudioFlinger(  283): closeInput() 16
V/AudioSystem(  283): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  283): ThreadBase::exit
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioSystem( 3112): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  283): RecordThread 0xb3e65000 exiting
D/audio_hw_primary(  283): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioSystem( 1375): ioConfigChanged() event 4, ioHandle 16
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioSystem( 1751): ioConfigChanged() event 4, ioHandle 16
V/AudioPolicyManager(  283): releaseInput() exit
V/AudioFlinger(  283): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  283): removeClient_l() pid 1939, calling pid 283
V/AudioSystem(  973): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1939): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2647): ioConfigChanged() event 4, ioHandle 16
I/HotwordRecognitionRnr( 1939): Stopping hotword detection.
I/HotwordRecognitionRnr( 1939): Hotword detection finished
D/ContextHelper( 5252): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5252): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5252): Time to load native libraries: 7 ms (timestamps 1575-1582)
I/LibraryLoader( 5252): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5252): Binding Chromium to main looper Looper (main, tid 1) {1207e067}
I/LibraryLoader( 5252): Expected native library version number "",actual native library version number ""
I/chromium( 5252): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5252): Initializing chromium process, singleProcess=true
W/art     ( 5252): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5252): ApplicationContext is null in ApplicationStatus
W/chromium( 5252): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5252): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5252): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5252): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5252): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5252): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5252): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5252): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5252): Remote Branch: 
I/Adreno-EGL( 5252): Local Patches: 
I/Adreno-EGL( 5252): Reconstruct Branch: 
V/AudioPolicyService(  283): registerClient() client 0xb3c15900, uid 10316
D/BluetoothManagerService(  973): Message: 20
D/BluetoothManagerService(  973): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2499e9a1:true
D/BluetoothAdapter( 5252): 1047463808: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5252): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5252): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5252): CordovaWebView is running on device made by: LGE
,W/art     ( 5252): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5252): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5252): Activity.onPostResume() called 
,D/OpenGLRenderer( 5252): Render dirty regions requested: true
I/OpenGLRenderer( 5252): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5252): Enabling debug mode 0
D/Atlas   ( 5252): Validating map...
,D/SplitWindow(  973): check instance of lgWin Window{34bf7d11 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5252): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  973): Focus entered window: Window{34bf7d11 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  973): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  973): Displayed com.test.thalitest/.MainActivity: +1s161ms
I/Timeline(  973): Timeline: Activity_windows_visible id: ActivityRecord{181ba64a u0 com.test.thalitest/.MainActivity t222} time:82259
I/Timeline( 5252): Timeline: Activity_idle id: android.os.BinderProxy@31580bf3 time:82275
,W/BindingManager( 5252): Cannot call determinedVisibility() - never saw a connection for the pid: 5252
,I/CheckinService( 4045): Done disabling old GoogleServicesFramework version
,D/JsMessageQueue( 5252): Set native->JS mode to OnlineEventsBridgeMode
,D/InitAlarmsService( 3565): Clearing and rescheduling alarms.
,I/ActivityManager(  973): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5318 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5318): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5318): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@214bb45a
,D/CalendarProvider2( 5318): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5318): Created com.android.providers.calendar.CalendarAlarmManager@1207e067(com.android.providers.calendar.CalendarProvider2@214bb45a)
D/CalendarProvider2( 5318): Scheduling check of next Alarm
,D/CalendarProvider2( 5318): SCHEDULE_ALARM_REMOVE
I/ActivityManager(  973): Killing 3565:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10013/pid_3565/cgroup.procs: No such file or directory
,D/jxcore_app_log( 5252): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618764800
,I/chromium( 5252): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/art     ( 5252): CheckpointMarkThreadRoots callback created = 0x9fa8e3c0
,I/art     ( 5252): CheckpointMarkThreadRoots callback created = 0x9fa8e390
,I/CalendarProvider2( 5318): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5318): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  973): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5354 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  973): Killing 5146:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10018/pid_5146/cgroup.procs: No such file or directory
W/ResourcesManager( 5354): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  973): Explicit concurrent mark sweep GC freed 26189(1397KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 1.701ms total 190.731ms
,D/CalendarApplication( 5354): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 5354): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 5354): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1b5b3368, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@19eec381, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@100bc26, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1207e067, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@a641e14, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@54316bd, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1ac74b2, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@35a81c03, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3e6f0780, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@368f61b9, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@38e929fe, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3e86755f, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3d7d1bac, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1fbb6075, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@29a9e80a, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3c7087b, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@a764698, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2f6e8ef1, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@21067ad6, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@20b3b157, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2cd53444, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3d4c292d, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@13c76e62, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@31580bf3, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@71350b0, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3def2b29, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@8b20eae, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3cdd744f, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@27d4c7dc, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3aa650e5, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1b9467ba, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@29a7066b, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1d485c8, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@8f01661, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@25114586, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@172d9e47, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@36903674, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3db6b79d, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@132c3412, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@399bd7e3, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1fb445e0, lg_preferences_recen,t_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@184c3099
D/GeneralPreferenceUtils( 5354): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,D/Config  ( 5354): [init]
I/Config  ( 5354): LGCalendar ver.4.40.17
I/Config  ( 5354): start check model
I/Config  ( 5354): start check native_ca
I/Config  ( 5354): Config Operator=OPEN, Country=EU
D/Config  ( 5354): [setDefaultValuesToPref]
D/Config  ( 5354): [parseProfiles]
D/ProfilesParser( 5354): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5354): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5354): [updateProfiletoCountryInfo]
D/GeneralPreference( 5354): [checkAndMigrateOldPreference]
,D/AlertReceiver( 5354): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 5354): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 5354): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 5354): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5354): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
,I/AlertUtils( 5354): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 5354): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 5354): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 5354): onHandleIntent
,D/HolidayDataLoader( 5354): readJsonAsset : holiday.json
D/AlertService( 5354): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 5354): [updateWidgets] 
D/MonthWidgetProvider( 5354): [onReceive]
D/CalendarWidgetProvider( 5354): [onReceive]
,D/CalendarWidgetProvider( 5354): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5354): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 5354): [onReceive]
D/CalendarWidgetProvider( 5354): [onReceive]
D/CalendarWidgetProvider( 5354): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5354): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 5354): onHandleIntent:holiday data empty
,W/jxcore-log( 5252): Initializing JXcore engine
,W/jxcore-log( 5252): JXcore engine is ready
W/Thread-606( 5347): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7712]" dev="sockfs" ino=7712 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-606( 5347): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-606( 5347): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6489]" dev="sockfs" ino=6489 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-606( 5347): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,W/Thread-606( 5347): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-606( 5347): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25626]" dev="sockfs" ino=25626 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5252): Starting JXcore engine
,W/jxcore-log( 5252): Platform android
W/jxcore-log( 5252): 
W/jxcore-log( 5252): Process ARCH arm
W/jxcore-log( 5252): 
,I/jxcore-log( 5252): JXcore Cordova bridge is ready!
I/jxcore-log( 5252): 
W/jxcore-log( 5252): JXcore engine is started
,I/jxcore-log( 5252): Toggling radios to true
I/jxcore-log( 5252): 
,D/BluetoothManagerService(  973): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  973): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  973): Message: 1
D/BluetoothManagerService(  973): MESSAGE_ENABLE: mBluetooth = null
D/BluetoothAdapterService(900209667)( 1985): onBind()
,D/BluetoothManagerService(  973): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/LocationManagerService(  973): getAllProviders()=[passive, gps, network]
D/BluetoothManagerService(  973): Message: 40
,D/BluetoothManagerService(  973): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/Ulp_jni (  973): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  973): JNI:system_update. Event-4
D/WifiServiceImplEx(  973): setWifiEnabled: true pid=5252, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  973): setWifiEnabled: true pid=5252, uid=10316
I/bluedroid( 1985): config_hci_snoop_log
,D/BluetoothManagerService(  973): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  973): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/LocationManagerService(  973): getAllProviders()=[passive, gps, network]
D/WifiServiceImplEx(  973): disconnect pid=5252, uid=10316, packageName=com.test.thalitest
D/Ulp_jni (  973): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  973): JNI:system_update. Event-4
D/WifiServiceImplEx(  973): reconnect pid=5252, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5252): Radios toggled
I/jxcore-log( 5252): 
I/jxcore-log( 5252): My device name is: LGE-LG-D722
I/jxcore-log( 5252): 
I/LGFTMITEM(  973): [GET_FTM][id=6], offset=12288
E/WifiHW  (  973): Wifi MAC Address = a0:39:f7:70:12:80
V/LGMDMManagerInternal( 1985): Create singleton instance
E/WifiHW  (  973): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  973): band=b
E/WifiHW  (  973): ": cur_etheraddr=a0:39:f7:70:12:80
,D/SoftapController(  276): Softap fwReload - Ok
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  276): Setting iface cfg
D/CommandListener(  276): Trying to bring down wlan0
D/CommandListener(  276): Clearing all IP addresses on wlan0
,E/WifiHW  (  973): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
I/wpa_supplicant( 5400): Successfully initialized wpa_supplicant
,D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
D/BluetoothAdapterService(900209667)( 1985): enable() - Enable called with quiet mode status =  false
D/BluetoothAdapterState( 1985): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 1985): Setting state to 11
D/WifiMonitor(  973): startMonitoring(wlan0) with mConnected = false
,I/BluetoothAdapterState( 1985): Bluetooth adapter state changed: 10-> 11
I/wpa_supplicant( 5400): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 5400): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/BluetoothAdapterService(900209667)( 1985): updateAdapterState() - Broadcasting state to 1 receivers.
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothManagerService(  973): Message: 60
D/BluetoothManagerService(  973): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  973): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothAdapterService(900209667)( 1985): processStart()
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:06.916 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
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
,W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1985): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(900209667)( 1985): processStart() - Make Bond State Machine
,D/BluetoothBondStateMachine( 1985): make
D/BluetoothAdapterService( 1985): setAdapterService() - set to: null
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
D/LGBluetoothServiceAdapter( 1985): [BTUI] check adapter is available - true : set adapter available.
,I/BluetoothBondStateMachine( 1985): StableState(): Entering Off State
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
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
D/BluetoothAdapterService(900209667)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.WIFI_STATE_CHANGED at null
I/ActivityManager(  973): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5412 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/WifiServerServiceExt(  973): WIFI_STATE_CHANGED_ACTION [2]
I/ActivityManager(  973): Process com.android.vending (pid 4856) has died
,D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(900209667)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
D/LGBluetoothAPIService( 1804): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/HeadsetService( 1985): Received start request. Starting profile...
I/[SystemUI]BluetoothHandler( 1375): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
D/BluetoothHeadset( 1751): Proxy object connected
D/BluetoothHeadset(  973): Proxy object connected
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(900209667)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
I/LGBluetoothHeadsetServiceJni( 1985): classInitNative: succeeds
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
,D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(900209667)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
D/LGBluetoothFeatureConfig( 1985): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 1985): classInitNative: succeeds
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(900209667)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/BluetoothHeadset( 1751): Proxy object connected
D/HeadsetStateMachine( 1985): make
D/BluetoothHeadset( 1751): Proxy object connected
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(900209667)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
,W/ResourcesManager( 5412): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5412): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 5412): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5412): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5412): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1985): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(900209667)( 1985): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1985): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(900209667)( 1985): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
,D/HeadsetStateMachine( 1985): max_hf_connections = 1
I/bluedroid( 1985): get_profile_interface handsfree
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
,W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1985): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(900209667)( 1985): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
I/bt-btif ( 1985): btif_hf_get_interface
I/bt-btif ( 1985): init
D/bt-btif ( 1985): max_hf_clients = 1
D/bt-btif ( 1985): btif_max_hf_clients = 1
D/bt-btif ( 1985): btif_enable_service: current services:0xa06d8330
D/BluetoothAdapterService( 1985): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1985): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 1985): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1985): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(900209667)( 1985): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
V/ToneGenerator( 1985): ToneGenerator constructor: streamType=8, volume=1.000000
,V/AudioPolicyService(  283): registerClient() client 0xb551c820, uid 1002
V/AudioPolicyManager(  283): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  283): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  283): getOutput() returns output 2
V/AudioFlinger(  283): registerClient() client 0xb40332b0, pid 1985
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  283): thread 0xb56eb000 type 0 TID 1293 waking up
V/AudioFlinger(  283): thread 0xb5651000 type 0 TID 1292 waking up
V/AudioFlinger(  283): thread 0xb5735000 type 0 TID 1295 waking up
V/AudioSystem( 1985): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioSystem(  283): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  283): ioConfigChanged() opening already existing output! 4
V/LGMDMManager( 1985): Create singleton instance
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem( 3112): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3112): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1375): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1751): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1751): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1939): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1939): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2647): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2647): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  283): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  283): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  973): ioConfigChanged() event 0, ioHandle 4
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem(  973): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3112): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3112): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  973): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  973): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1751): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1751): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1939): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1939): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2647): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2647): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1375): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  283): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1375): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  283): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1751): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1751): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 1375): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1939): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1939): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2647): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2647): ioConfigChanged() opening already existing output! ,2
V/AudioSystem( 1375): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1375): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3112): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3112): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  973): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  973): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1985): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1985): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 1985): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1985): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem( 1985): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1985): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/ToneGenerator( 1985): Create Track: 0xb4909480
V/AudioTrack( 1985): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 1985): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
I/AudioFlinger(  283): isAudioPlaybackHookOn() false
D/AudioTrack( 1985): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  283): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  283): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  283): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  283): getOutput() returns output 2
V/AudioSystem( 1985): getLatency() output 2, latency 50
V/AudioSystem( 1985): getFrameCount() output 2, frameCount 960
V/AudioTrack( 1985): createTrack_l() output 2 afLatency 50
V/AudioTrack( 1985): Create normal PCM 0x1 Track
V/AudioFlinger(  283): createTrack() lSessionId: 21
V/AudioFlinger(  283): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 1
I/BluetoothAdapterState( 1985): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
V/AudioTrack( 1985): Flags here  0x4 
V/AudioTrack( 1985): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  283): acquiring 21 from 1985, for 1985
V/AudioFlinger(  283):  added new entry for 21
V/ToneGenerator( 1985): ToneGenerator INIT OK, time: 86494
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
D/HeadsetStateMachine( 1985): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb5651000
D/HeadsetPhoneState( 1985): [BTUI] listenForPhoneState : start = false
D/BluetoothA2dp(  973): Proxy object connected
D/LGBluetoothHfpManager( 1985): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1985): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  283): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1985
D/audio_hw_primary(  283): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  283): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  283): platform_set_parameters: enter: bt_samplerate=8000
D/A2dpService( 1985): Received start request. Starting profile...
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
V/ToneGenerator( 1985): ToneGenerator destructor
V/ToneGenerator( 1985): stopTone
V/ToneGenerator( 1985): Delete Track: 0xb4909480
I/BluetoothAvrcpServiceJni( 1985): classInitNative: succeeds
V/AudioTrack( 1985): ~AudioTrack, releasing session id from 1985 on behalf of 1985
V/AudioFlinger(  283): remove track (4099) and delete from mixer
V/AudioPolicyService(  283): AudioCommandThread() adding release output 2
V/AudioPolicyService(  283): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing release output 2
V/AudioFlinger(  283): releasing 21 from 1985 for 1985
V/AudioPolicyManager(  283): releaseOutput() 2
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioFlinger(  283): PlaybackThread::Track destructor
V/AudioFlinger(  283): removeClient_l() pid 1985, calling pid 283
V/Avrcp   ( 1985): make
D/Avrcp   ( 1985): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 1985): get_profile_interface avrcp
I/bt-btif ( 1985): btif_rc_get_interface
I/bt-btif ( 1985): ## init ##
I/LGBluetoothAvrcpServiceJni( 1985): classInitNative: succeeds
I/LGBluetoothAvrcpAdapter( 1985): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 1985): initNative: succeeds
I/BluetoothAvrcpBrcmAdapterJni( 1985): classInitBrcmNative
,I/BluetoothAvrcpBrcmAdapterJni( 1985): initBrcmNative
I/IndexDatabaseHelper( 5412): Using schema version: 115
I/IndexDatabaseHelper( 5412): Index is fine
,V/AudioService(  973): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,E/AudioService(  973): No RCC entry present to update
E/RemoteController( 1985): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 1985): classInitNative
I/BluetoothA2dpServiceJni( 1985): classInitNative: succeeds
D/A2dpStateMachine( 1985): make
I/bluedroid( 1985): get_profile_interface a2dp
I/bt-btif ( 1985): btif_av_get_src_interface
I/bt-btif ( 1985): init
D/bt-btif ( 1985): btif_enable_service: current services:0xa06d8330
I/LGBluetoothA2dpServiceJni( 1985): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1985): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 1985): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 1985): [BTUI] init
D/LGBluetoothPowerControlManager( 1985): [BTUI] init : getProfileProxy
D/BluetoothManagerService(  973): Message: 30
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
I/BluetoothHidServiceJni( 1985): classInitNative: succeeds
,D/HidService( 1985): Received start request. Starting profile...
I/bluedroid( 1985): get_profile_interface hidhost
I/bt-btif ( 1985): btif_hh_get_interface
I/bt-btif ( 1985): init
D/bt-btif ( 1985): btif_enable_service: current services:0xa06d8330
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
I/BluetoothHealthServiceJni( 1985): classInitNative: succeeds
D/HealthService( 1985): Received start request. Starting profile...
D/A2dpStateMachine( 1985): Enter Disconnected: -2
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
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
I/BluetoothPanServiceJni( 1985): classInitNative(L105): succeeds
D/PanService( 1985): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1985): initializeNative(L110): pan
I/bluedroid( 1985): get_profile_interface pan
D/bt-btif ( 1985): stack_initialized = 0, btpan_cb.enabled:0
,I/LGBluetoothPanAdapter( 1985): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
I/BtGatt.JNI( 1985): classInitNative(L901): classInitNative: Success!
,D/BtGatt.DebugUtils( 1985): handleDebugAction() action=null
D/BtGatt.GattService( 1985): Received start request. Starting profile...
D/BtGatt.GattService( 1985): start()
I/bluedroid( 1985): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 1985): advertise manager created
I/LGBluetoothGattAdapter( 1985): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 1985): setGattService:  set to: null
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
I/LGBluetoothMapAdapter( 1985): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1985): BluetoothMapBinder()
,D/BluetoothMapService( 1985): Received start request. Starting profile...
D/BluetoothMapService( 1985): start()
D/BluetoothMapEmailSettingsLoader( 1985): Found 0 applications
D/BluetoothMapEmailAppObserver( 1985): createReceiver()
D/BluetoothMapEmailAppObserver( 1985): initObservers()
D/BluetoothMapEmailAppObserver( 1985): getEnabledAccountItems()
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
,I/BluetoothSAPServiceJni( 1985): classInitNative(L170): succeeds
D/SapService( 1985): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1985): initializeNative(L175): sap
I/bluedroid( 1985): get_profile_interface sap
I/bt-btif ( 1985): btif_sc_get_interface
I/bt-btif ( 1985): init
D/bt-btif ( 1985): btif_enable_service: current services:0xa06d8330
I/LGBluetoothSapAdapter( 1985): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1985): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1985): [BTUI] initSapManager
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
D/LgeBluetoothSimManager( 1751): [BTUI] SAP_ENABLE_EVT
,V/BluetoothFTPServiceJni( 1985): classInitNative
I/BluetoothFTPServiceJni( 1985): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
D/BluetoothFTPService( 1985): BluetoothFtpBinder()
D/**BluetoothFTPService( 1985): Received start request. Starting profile...
V/BluetoothFTPService( 1985): FTP-Server Service start
D/BluetoothFTPServiceJni( 1985): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1985): get_profile_interface ftp
I/bt-btif ( 1985): btif_fts_get_interface
I/bt-btif ( 1985): init
D/bt-btif ( 1985): btif_enable_service: current services:0xa06d8330
D/BluetoothFTPServiceJni( 1985): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
D/HeadsetStateMachine( 1985): Proxy object connected
D/LGBluetoothHfpAdapter( 1985): [BTUI] queryPhoneState
D/LGBluetoothFeatureConfig( 1985): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 1985): classInitNative
I/BluetoothOPPServiceJni( 1985): classInitNative(L373): succeeds
V/OppService( 1985): Opp initBinder
,D/**OppService( 1985): Received start request. Starting profile...
D/OppService( 1985): Starting OppService 
D/LGBluetoothOppAdapter( 1985): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/NotificationManager( 1985): com.android.bluetooth: cancelAll by com.android.bluetooth
V/BluetoothOppNotification( 1985): send message
D/BluetoothOppPreference( 1985): Dumping Names:  
D/BluetoothOppPreference( 1985): {}
D/BluetoothOppPreference( 1985): Dumping Channels:  
D/BluetoothOppPreference( 1985): {}
D/OppService( 1985): Start()
W/BluetoothOPPServiceJni( 1985): initOppNative
D/BluetoothOPPServiceJni( 1985): initOppNative(L383): OPP
I/bluedroid( 1985): get_profile_interface opp
I/bt-btif ( 1985): btif_op_get_interface
,D/BluetoothOPPServiceJni( 1985): initOppNative(L411): mOppCallbacksObj 1049854
D/BluetoothOPPServiceJni( 1985): initOppNative(L413): calling OPP init
V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
I/bt-btif ( 1985): btif_opp_init
D/bt-btif ( 1985): btif_enable_service: current services:0xa06d8330
D/BluetoothOPPServiceJni( 1985): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 1985): initOppNative(L430): mOppCallbacksObj 1049854
V/OppService( 1985): setOppService(): set to: com.broadcom.bt.service.opp.OppService@17545941
D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(900209667)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1985): pendingUpdate is :  true
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothA2dp( 1985): Proxy object connected
D/LGBluetoothPowerControlManager( 1985): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@2b61fee6
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(900209667)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 1985): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1985): Disconnected process message: 11, size: 0
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(900209667)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1985): Deleted complete outbound shares, number =  0
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(900209667)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1985): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 1985): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 1985): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(900209667)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(900209667)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1985): Handler(): got msg=1
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(900209667)( 1985): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - Message: 1
,D/BluetoothAdapterService(900209667)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(900209667)( 1985): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothPbapReceiver( 1985): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1985): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1985): ***********state = 11
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(900209667)( 1985): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@cc487d on behalf of 
D/BluetoothAdapterService( 1985): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 1985): new notify threadi!
V/BluetoothOppNotification( 1985): send delay message
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - Message: 1
D/BluetoothAdapterService(900209667)( 1985): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(900209667)( 1985): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 1985): isTurningOnRadio()=false
D/BluetoothAdapterState( 1985): isTurningOffRadio()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1985): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1985): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(900209667)( 1985): onProfileServiceStateChange() - All profile services started.
V/OppService( 1985): ContentObserver received notification
V/OppService( 1985): ContentObserver received notification
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/BluetoothAdapterState( 1985): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1985): enable
I/bt-btif ( 1985): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1985): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
I/bt_hci_bdroid( 1985): init
I/bt_vendor( 1985): init
I/bt_vnd_conf( 1985): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 1985): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1985): libbt-hci init returns 0
I/GKI_LINUX( 1985): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 1985): btu_task pending for preload complete event
,D/WiFiOffLoadUpdatePriority( 5412): remove : truetruefalse
D/WiFiOffLoadUpdatePriority( 5412): remove2
V/WiFiOffLoadSharedPrefsUtils( 5412): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 5412): save remove
D/WiFiOffLoadBroadcast( 5412): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5412): S: false, R: true
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@22bf2372 on behalf of 
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@245b03c3 on behalf of 
,V/BluetoothOppNotification( 1985): mUpdateCompleteNotification = true
V/OppService( 1985): pendingUpdate is :  true
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@21b83440 on behalf of 
V/BluetoothOppNotification( 1985): update too frequent, put in queue
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@24d9ef79 on behalf of 
,V/BluetoothOppNotification( 1985): outbound: succ-0  fail-0
V/OppService( 1985): pendingUpdate is :  false
E/OppService( 1985): UpdateThread is Completed
I/NotificationManager( 1985): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1985): outbound notification was removed.
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@85804be on behalf of 
V/BluetoothOppNotification( 1985): inbound: succ-0  fail-0
,I/ActivityManager(  973): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5454 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/bt_userial_vendor( 1985): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 1985): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1985): device fd = 71 open
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 21.506ms
D/bt_hwcfg( 1985): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 1985): hw_config_cback state=1
,I/NotificationManager( 1985): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1985): inbound notification was removed.
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
D/BluetoothPermissionRequest( 5412): onReceive
D/LGBluetoothFeatureConfig( 5412):  get() - isFeatureLoaded : false
,V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@7e0191f on behalf of 
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.366ms
D/bt_hwcfg( 1985): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 1985): hw_config_cback state=4
D/bt_hwcfg( 1985): Chipset Name: BCM4334B0
D/bt_hwcfg( 1985): Chipset BCM4334B0
D/bt_hwcfg( 1985): Target name = [BCM4334B0]
I/bt_hwcfg( 1985): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1985): hw_config_cback state=2
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.810ms
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1985): hw_config_cback state=3
I/bt_hwcfg( 1985): bt vendor lib: set UART baud 4000000
D/BluetoothManagerService(  973): Message: 20
D/BluetoothManagerService(  973): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@324e9ec5:true
V/BluetoothSapReceiver( 1985): [BTUI] checkServiceStart
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 1985): hw_config_cback state=5
,D/LGBluetoothStateChangeReceiver( 1985): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
I/ActivityManager(  973): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5474 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/PCSuite ( 5454): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/ActivityManager(  973): Killing 5165:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
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
W/libprocessgroup(  973): failed to open /acct/uid_10069/pid_5165/cgroup.procs: No such file or directory
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
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
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
W/ResourcesManager( 5474): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/Tethering(  973): sendTetherStateChangedBroadcast 1, 0, 0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  973): DNSproblemNotiEnabled is disabled ignore DNS fail CB
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
D/UsbSettingsReceiver( 5412): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5412): [AUTORUN] sys.usb.config = ptp_only,adb
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/UsbSettingsReceiver( 5412): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5412): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1985): hw_config_cback state=6
D/UsbSettingsReceiver( 5412): [AUTORUN] onReceive() : app userid = 0, current userid = 0
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
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/LGBluetoothProfileConnectionReceiver_EasySetting( 5474): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
E/wpa_supplicant( 5400): USIM:  scard_init function
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/wpa_supplicant( 5400): rfkill: Cannot open RFKILL control device
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/AuthorizationBluetoothService( 1734): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 9
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/UsbSettingsControl( 5412): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 5412): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5412): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5412): [AUTORUN] onReceive() : errorList=[]
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/UsbSettingsControl( 5412): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/bt_hwcfg( 1985): hw_config_cback state=6
D/UsbSettingsReceiver( 5412): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/UsbSettingsControl( 5412): [AUTORUN] setTetherStatus() : status=false
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/ActivityManager(  973): Killing 4792:com.google.android.apps.plus/u0a86 (adj 15): empty #11
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
I/wpa_supplicant( 5400): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
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
,D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
I/wpa_supplicant( 5400): wlan0: CTRL-EVENT-SCAN-STARTED 
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/WifiStateMachine(  973): MAC Addr from driver = a0:39:f7:70:12:80
D/WifiOffDelayIfNotUsed(  973): setPowerSaveActivated(false)
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
W/libprocessgroup(  973): failed to open /acct/uid_10086/pid_4792/cgroup.procs: No such file or directory
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:07.974 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/WifiServerServiceExt(  973): WIFI_STATE_CHANGED_ACTION [3]
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/WifiServerServiceExt(  973): batteryPsActivateMsgHandler : state:0 event:3
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
E/WifiServerServiceExt(  973): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
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
D/WiFiOffLoadUpdatePriority( 5412): remove : truetruetrue
E/WifiConfigStore(  973): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
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
,D/WifiStateMachine(  973): enableVerboseLogging : level 2
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
D/WifiStateMachine(  973): Setting OUI to DA-A1-19
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/WifiNative-HAL(  973): Setting external_sim to 1
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/WifiNative-HAL(  973): startHal
E/wifi    (  973): getStaticLongField sWifiHalHandle 0x9ac068ec
I/WifiHAL (  973): Initializing wifi
I/WifiHAL (  973): Creating socket
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
I/WifiHAL (  973): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  973): Did set static halHandle = 0xb06af240
D/wifi    (  973): halHandle = 0xb06af240, mVM = 0xb487c280, mCls = 0xa01c1e
E/wifi    (  973): getStaticLongField sWifiHalHandle 0x9ac0689c
D/wifi    (  973): array field set
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/WifiNative-HAL(  973): interface[0] = wlan0
I/WifiNative-HAL(  973): interface[1] = p2p0
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/wifi    (  973): setting scan oui 0xb04957a8
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/WifiHAL (  973): Sending mac address OUI
D/bt_hwcfg( 1985): hw_config_cback state=6
E/WifiHAL (  973): failed to set scanning mac OUI; result = -95
D/WifiStateMachine(  973): Setting OUI to DA-A1-19
I/WifiNative-HAL(  973): startHal
D/wifi    (  973): setting scan oui 0xb04957a8
D/WifiHAL (  973): Sending mac address OUI
E/WifiHAL (  973): failed to set scanning mac OUI; result = -95
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
I/WifiNative-HAL(  973): Waiting for HAL events mWifiHalHandle=-1335168448
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/wifi    (  973): waitForHalEvents called, vm = 0xb487c280, obj = 0xa01c1e, env = 0x9dc0efd0
E/wifi    (  973): getStaticLongField sWifiHalHandle 0x97de5b2c
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
W/Settings( 4986): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1985): hw_config_cback state=6
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 1985): hw_config_cback state=6
D/WfdsService( 1804): Supplicant Connection state is changed : true
D/WfdsService( 1804): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1804): Set the WFDS Monitor: true
D/WfdsMonitor( 1804): WfdsMonitorThread create
D/WfdsMonitor( 1804): WFDS Monitor is created and started
D/WfdsService( 1804): WiFi: Supplicant connection re-established
E/CtrlSupplicant( 1804): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1804): Succeed to open control connection
E/CtrlSupplicant( 1804): Succeed to open monitor connection
D/WfdsMonitor( 1804): Supplicant connection established
D/WfdsService( 1804): Connected to the supplicant for wfds
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,D/WifiHS20(  973): hidePasspointNotification off =false
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:08.033 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService(  973): SCAN_AVAILABLE : 3
D/RttService(  973): SCAN_AVAILABLE : 3
D/RttService(  973): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  973): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  973): startHal
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/LGWifiP2pService(  973): P2pDisabledState{ when=-2ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiServerServiceExt(  973): set CMD_ADD_DEFAULT_PROFILE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/WifiServerServiceExt(  973): setWifiDualbandAPConnection band : 1
D/wifi    (  973): getting scan capabilities on interface[0] = 0xb04957a8
D/WifiHAL (  973): Creating message to get scan capablities; iface = 24
D/wifi    (  973): failed to get capabilities : -95
E/wpa_supplicant( 5400): nWIFIDualbandAPConnection: 1
E/WifiScanningService(  973): could not get scan capabilities
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  276): Setting iface cfg
D/CommandListener(  276): Trying to bring up p2p0
D/WifiMonitor(  973): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService(  973): P2pEnablingState
I/WifiServerServiceExt(  973): set CMD_DISCONNECT_RSSI_LVL : -100
D/LGWifiP2pService(  973): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): P2p socket connection successful
E/wpa_supplicant( 5400): disconnect_rssi_lvl: -100
D/LGWifiP2pService(  973): P2pEnabledState
I/WifiServerServiceExt(  973): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
E/wpa_supplicant( 5400): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
D/LGWifiP2pService(  973): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  973): before postfix = G3s-1
D/WifiServerServiceExt(  973): postfix byte check : 5
D/LGWifiP2pService(  973): after postfix = G3s-1
I/WifiServerServiceExt(  973): set CMD_UPDATE_DEFAULT_PROFILE
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
,D/WifiNative-HAL(  973): p2pGetDeviceAddress
I/wpa_supplicant( 5400): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,I/wpa_supplicant( 5400): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-HAL(  973): p2pGetDeviceAddress returning a2:39:f7:70:12:80
D/LGWifiP2pService(  973): DeviceAddress: a2:39:f7:70:12:80
,D/WfdsService( 1804): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1804): Update P2p Interface State: 3
I/bt_hwcfg( 1985): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 1985): Settlement delay -- 100 ms
I/bt_hwcfg( 1985): Setting fw settlement delay to 100 
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 5400): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/LGWifiP2pService(  973): sending p2p persistent groups changed broadcast
,D/LGWifiP2pService(  973): sending p2p connection changed broadcast
D/LGWifiP2pService(  973): InactiveState
D/LGWifiP2pService(  973): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): InactiveState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): P2pEnabledState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): DefaultState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1804): WifiP2pState is changed : true
E/WifiServerServiceExt(  973): No p2p device connected
D/WfdsService( 1804): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsService( 1804): Receive the WFDS_ENABLE Method
D/WfdsService( 1804): Set the WFDS Monitor: true
D/WfdsService( 1804): Connected to the supplicant for wfds
D/WfdsJNI ( 1804): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 5400): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1804): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 5400): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WfdsJNI ( 1804): doCommand: WFDS_CLEAR_PD_INFO
I/wpa_supplicant( 5400): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WfdsJNI ( 1804): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:08.146 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WfdsJNI ( 1804): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/WfdsService( 1804): selectPreferredScanChannel [6]
D/WfdsService( 1804): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
D/LGWifiP2pService(  973): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1804): isConnected: false
D/WfdsService( 1804): GroupInfoAvailable: mGroupInfo is null
W/WfdsService( 1804): DefaultState - msg [9441285] is not handled
,D/WiFiOffLoadUpdatePriority( 5412): remove1
V/WiFiOffLoadSharedPrefsUtils( 5412): save remove
,I/wpa_supplicant( 5400): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5400): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
D/WiFiOffLoadBroadcast( 5412): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5412): S: false, R: false
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
,D/LocSvc_java(  973): onReceive
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:08.18 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:08.187 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/GONS    ( 1751): GONS isTestMode: false Country: 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:08.201 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:08.202 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/WifiServerServiceExt(  973): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  973): setSupplicantStateSCANNING
,I/WifiServiceExtension(  973): setVHTCapabilityType  : false
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1985): hw_config_cback state=2
,I/WifiServerServiceExt(  973): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  973): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1985): hw_config_cback state=7
I/bt_hwcfg( 1985): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 1985): Setting local bd addr to F8:95:C7:87:85:54
I/WifiServiceExtension(  973): setSecurityType  : 2
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:08.249 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:08.25 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/bt_hwcfg( 1985): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 1985): hw_config_cback state=8
I/bt_hwcfg( 1985): vendor lib fwcfg completed
I/bt-btif ( 1985): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 1985): btu_task received preload complete event
,D/WifiExtManager(  973): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@278e0296
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
D/ConnectivityService(  973): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  973): Got NetworkAgent Messenger
,D/ConnectivityService(  973): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  973): NetworkAgent connected
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
E/WifiConfigStore(  973): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  973): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/ActivityManager(  973): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5502 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  973): RTC_WAKEUP set : Alarm{19089a70 type 0 when 1454534047356 com.android.vending} when 1454534047356
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  276): Setting iface cfg
D/DhcpStateMachine(  973): StoppedState
E/WifiStateMachine(  973): Start Dhcp Watchdog 1
D/DhcpStateMachine(  973): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  973): WaitBeforeStartState
D/WiFiOffLoadUpdatePriority( 5412): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5412): connected SSID: null
D/WifiServerServiceExt(  973): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  973): setSupplicantStateGROUP_HANDSHAKE
,D/WiFiOffLoadUpdatePriority( 5412): private wpa: "NG700" 300
D/ConnectivityService(  973): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/WifiServiceImplEx(  973): addOrUpdateNetwork pid=5412, uid=1000, packageName=android.uid.system:1000
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
E/addOrUpdateNetwork(  973):  uid = 1000 SSID "NG700" nid=0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-64 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:08.342 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
,D/LGWifiP2pService(  973): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a3ce0a3 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  973): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService(  973): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a3ce0a3 target=com.android.internal.util.StateMachine$SmHandler }
,V/DhcpStateMachine(  973): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  973): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  973): DHCP Start wake lock is acquired.
E/bt-btif ( 1985): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
V/LgDhcpStateMachineHelper(  973): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
I/GKI_LINUX( 1985): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 1985): warning : media task started media_task_refcnt 1 
,W/bt-smp  ( 1985): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1985): Plain text(LSB ~ MSB) = e1 bd 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1985): Encrypted text(LSB ~ MSB) = 77 14 68 71 5d 15 36 ce 2a 75 77 b6 62 1b 4c 57 
D/BT_PROF_AUDIO( 1985): created moving average (N=100)
D/BT_PROF_AUDIO( 1985): reset rate average
W/bt-btif ( 1985): overflow 0, enter 0, exit 0
W/bt-btm  ( 1985): Stopping oneshot timer
V/LgDhcpStateMachineHelper(  973): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
E/bt-btif ( 1985): Calling BTA_HhEnable
E/bt-btif ( 1985): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 1985): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1985): Address is:F8:95:C7:87:85:54
D/WifiServerServiceExt(  973): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  973): setSupplicantStateCOMPLETED
D/BluetoothAdapterProperties( 1985): Name is: G3s-1
D/WifiServerServiceExt(  973): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  973): setSupplicantStateCOMPLETED
D/BluetoothManagerService(  973): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  973): Stored Bluetooth name: G3s-1
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
D/IOP_DB_BT( 1985): db_open: db_open : handle 2691573724l, read 11046 bytes onto local cache
D/IOP_DB_BT( 1985): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
E/WifiConfigStore(  973):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/IOP_DB_BT( 1985): db_query: result 1
I/        ( 1985): iop_db_open: iop_db_open status 0
E/bt-btif ( 1985): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 1985): btsock_ctrl_hci_init(L191): poll handle:6
,I/bt-btif ( 1985): bta_pan_co_init
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
E/bt-btif ( 1985): btif_hf_upstreams_evt: wrong handle = 12346 
I/bt-btif ( 1985): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 1985): opc_state_cb(L140):  opc_state_cb state:0
D/OppService( 1985): onOpcStateChange()
I/bt-btif ( 1985): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1985): ops_state_cb(L223):  ops_state_cb state:0
D/OppService( 1985): onOpsStateChange() :0
I/bt-btif ( 1985): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1985): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1985): onFtpServerEnabled: /storage
D/BluetoothPanServiceJni( 1985): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 1985): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1985): ScanMode =  20
D/BluetoothAdapterProperties( 1985): State =  11
D/BluetoothAdapterProperties( 1985): mDiscoverableTimeout = 120
D/OppService( 1985): Recieved MESSAGE_OPC_ENABLE
D/BluetoothAdapterProperties( 1985): Setting state to 12
I/BluetoothAdapterState( 1985): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(900209667)( 1985): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  973): Message: 60
I/bt-btif ( 1985): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  973): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  973): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothA2dp(  973): onBluetoothStateChange: up=true
D/LGBluetoothFeatureConfig( 1985): isPrivacyLogsEnabled : true
D/BluetoothAdapterProperties( 1985): Scan Mode:21
I/bt-btif ( 1985): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 1985): Entering On State
D/BluetoothAdapterProperties( 1985): Discoverable Timeout:120
I/BluetoothAdapterState( 1985): Entering On State from state = 11
D/BluetoothHeadset( 1751): onBluetoothStateChange: up=true
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
D/BluetoothHeadset( 1751): onBluetoothStateChange: up=true
D/BluetoothAdapterService(900209667)( 1985): isQuetModeEnabled() - Enabled = false
D/BluetoothHeadset(  973): onBluetoothStateChange: up=true
D/BluetoothAdapterService(900209667)( 1985): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1985): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1751): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1985): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 1985): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1985): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 1985): [BTUI]         local_name: G3s-1
D/OppService( 1985): Recieved MESSAGE_OPS_ENABLE
E/BluetoothManagerService(  973): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  973): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
D/BluetoothAdapterService(900209667)( 1985): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(900209667)( 1985): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1985): [BTUI] autoConnect() : not allowed
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterPr,operties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
D/LGBluetoothAPIService( 1804): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1375): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,D/BluetoothManagerService(  973): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
I/BluetoothMapService( 1985): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1985): STATE_ON
D/LGBluetoothAPIService( 1804): Message: 1
D/bt_h4   ( 1985): vendor lib postload completed
D/LGBluetoothAPIService( 1804): MESSAGE_BOOT_COMPLETED
I/LGBluetoothAPIService( 1804): [BTUI] LGBluetoothAPIService Binding Success
,D/BluetoothAdapterService( 1985): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35a81c03
D/BluetoothManagerService(  973): Message: 40
D/BluetoothManagerService(  973): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
V/BluetoothPbapService( 1985): Pbap Service onCreate
V/BluetoothPbapService( 1985): Starting PBAP service
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
D/LGBluetoothPbapAdapter( 1985): [BTUI] getInstance : create
V/BluetoothPbapService( 1985): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1985): state: 12
V/BluetoothMapService( 1985): Handler(): got msg=1
,D/BluetoothMapMasInstance( 1985): Map Service startRfcommSocketListener
D/LGBluetoothAPIServer( 1985): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1985): [BTUI] onBind()
D/LGBluetoothAPIService( 1804): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1804): Message: 100
D/LGBluetoothAPIService( 1804): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothOppNotification( 1985): new notify threadi!
E/WifiConfigStore(  973): Setting BSSID for "NG700"WPA_PSK to any
V/BluetoothOppNotification( 1985): send delay message
V/BluetoothPbapService( 1985): Handler(): got msg=1
V/BluetoothPbapService( 1985): Pbap Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 1985): MAS initSocket()
D/BluetoothMapMasInstance( 1985):   masId = 00
D/BluetoothMapMasInstance( 1985):   msgTypes = 0e
D/BluetoothMapMasInstance( 1985):   masName = SMS/MMS
D/BluetoothMapMasInstance( 1985):   SDP string = 000eSMS/MMS
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothPbapService( 1985): Pbap Service initSocket
D/BluetoothManagerService(  973): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  973): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@f0baeca on behalf of 
W/BluetoothAdapter( 1985): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 1985): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvCreateRecordByUser
I/bt-btif ( 1985): BTA_JvRfcommStartServer
I/bt-btif ( 1985): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1985): [BTUI] createSocketChannel FD=86 mFd=0
D/LGBluetoothServiceAdapter( 1985): [BTUI] createSocketChannel FD=84 mFd=86
V/BluetoothMapMasInstance( 1985): Succeed to create listening socket 
V/BluetoothPbapService( 1985): Succeed to create listening socket 
D/BluetoothMapMasInstance( 1985): Accepting socket connection...
V/BluetoothPbapService( 1985): Accepting socket connection...
D/WiFiOffLoadUpdatePriority( 5412):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5412): configuration updated: 0
V/BluetoothOppNotification( 1985): mUpdateCompleteNotification = true
I/WifiServerServiceExt(  973): set CMD_UPDATE_DEFAULT_PROFILE
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@3177283b on behalf of 
V/BluetoothOppNotification( 1985): outbound: succ-0  fail-0
,I/NotificationManager( 1985): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1985): outbound notification was removed.
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@36a04b58 on behalf of 
V/BluetoothOppNotification( 1985): inbound: succ-0  fail-0
I/NotificationManager( 1985): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1985): inbound notification was removed.
V/BluetoothOppProvider( 1985): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1985): created cursor android.database.sqlite.SQLiteCursor@374514b1 on behalf of 
D/WiFiOffLoadUpdatePriority( 5412): configuration saved: true
,D/PCSuite ( 5454): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{2cc10015 type 2 when 87826 com.google.android.gms} when 87826
W/ContextImpl( 5412): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/BluetoothPbapReceiver( 1985): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1985): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1985): ***********state = 12
,I/ActivityManager(  973): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5529 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{13e283f6 type 2 when 87900 com.android.providers.calendar} when 87900
D/DhcpStateMachine(  973): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  973): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  973): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/dhcpcd  ( 5535): version 5.5.6 starting
E/dhcpcd  ( 5535): get_duid: Read-only file system
,D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
,D/LocalBluetoothProfileManager( 5412): Adding local A2DP profile
D/BluetoothManagerService(  973): Message: 30
D/LocalBluetoothProfileManager( 5412): Adding local HEADSET profile
,D/BluetoothManagerService(  973): Message: 30
D/BluetoothManagerService(  973): Message: 30
D/BluetoothManagerService(  973): Message: 30
,D/LocalBluetoothProfileManager( 5412): Adding local MAP profile
D/BluetoothMap( 5412): Create BluetoothMap proxy object
D/BluetoothManagerService(  973): Message: 30
D/BluetoothManagerService(  973): Message: 30
,V/BluetoothPbapService( 1985): Pbap Service onBind
D/LocalBluetoothProfileManager( 5412): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 5412): [BTUI] initUserBindClient
,W/ContextImpl( 5412): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
I/dhcpcd  ( 5535): wlan0: rebinding lease of 192.168.1.134
,D/DockEventReceiver( 5412): finishStartingService: stopping service
D/BluetoothA2dp( 5412): Proxy object connected
D/A2dpProfile( 5412): Bluetooth service connected
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
D/BluetoothHeadset( 5412): Proxy object connected
D/HeadsetProfile( 5412): Bluetooth service connected
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
,D/BluetoothInputDevice( 5412): Proxy object connected
D/HidProfile( 5412): Bluetooth service connected
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
D/BluetoothPan( 5412): BluetoothPAN Proxy object connected
D/PanProfile( 5412): Bluetooth service connected
D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
D/BluetoothMap( 5412): Proxy object connected
D/MapProfile( 5412): Bluetooth service connected
D/BluetoothMap( 5412): getConnectedDevices()
,D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
V/BluetoothMapService( 1985): getConnectedDevices()
D/BluetoothPbap( 5412): Proxy object connected
D/PbapServerProfile( 5412): Bluetooth service connected
D/LGBluetoothUserBindClient( 5412): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 5412): onReceive
,D/LGBluetoothFeatureConfig( 5412): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 5412): [BTUI] FileNotFound: readProperty
V/BluetoothOppReceiver( 1985): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,V/BluetoothOppManager( 1985): restoreApplicationData! falsefalsenullnull
V/BluetoothSapReceiver( 1985): [BTUI] checkServiceStart
,D/LGBluetoothStateChangeReceiver( 1985): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/AuthorizationBluetoothService( 1734): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/Finsky  ( 5502): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LGDMClient( 5529): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5529): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 5529): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 5529): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5412): MCCMNC not supported: null
,D/LGDMClient( 5529): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5529): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/PCSuite ( 5454): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 5454): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5454): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 5529): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  973): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5577 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 6
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/Finsky  ( 5502): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5502): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5502): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 5502): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3135): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@3db6b79d on behalf of 5502
I/ActivityManager(  973): Killing 4986:com.google.android.talk/u0a61 (adj 15): empty #11
,D/Ads     ( 5502): Skipping gmscore version check
I/art     (  973): Explicit concurrent mark sweep GC freed 52972(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.398ms total 180.482ms
,W/libprocessgroup(  973): failed to open /acct/uid_10061/pid_4986/cgroup.procs: No such file or directory
,D/Finsky  ( 5502): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 5502): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5502): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5502): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/[BNRBootReceiver]( 5577): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5577): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5577): Boot Receiver Return
W/MainApplication( 5577): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5412): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 5412): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5412): MCCMNC not supported: null
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  973): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5412): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5412): MCCMNC not supported: null
D/Finsky  ( 5502): [635] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5502): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  973): Process com.google.android.gm (pid 4931) has died
V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5412): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5412): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5412): MCCMNC not supported: null
I/ActivityManager(  973): Killing 5318:com.android.providers.calendar/u0a14 (adj 15): empty #11
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  973): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,W/BroadcastQueue(  973): Exception when sending broadcast to ComponentInfo{com.android.providers.calendar/com.android.providers.calendar.CalendarProviderBroadcastReceiver}
W/BroadcastQueue(  973): android.os.DeadObjectException
W/BroadcastQueue(  973): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  973): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  973): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
W/BroadcastQueue(  973): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:270)
W/BroadcastQueue(  973): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1002)
W/BroadcastQueue(  973): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16810)
W/BroadcastQueue(  973): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
W/BroadcastQueue(  973): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/BroadcastQueue(  973): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/BroadcastQueue(  973): 	at android.os.Binder.execTransact(Binder.java:446)
W/libprocessgroup(  973): failed to open /acct/uid_10014/pid_5318/cgroup.procs: No such file or directory
,I/ActivityManager(  973): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5612 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  973): Spurious death for ProcessRecord{3b147c73 5612:com.android.providers.calendar/u0a14}, curProc for 5318: null
,W/ResourcesManager( 5612): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/dhcpcd  ( 5535): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,D/CalendarProvider2( 5612): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@214bb45a
D/CalendarProvider2( 5612): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5612): Created com.android.providers.calendar.CalendarAlarmManager@1207e067(com.android.providers.calendar.CalendarProvider2@214bb45a)
D/CalendarProviderBroadcastReceiver( 5612): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5612): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5612): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 5612): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 5612): [getOrCreateCalendarAlarmManager]
I/dhcpcd  ( 5535): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  973): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/ActivityManager(  973): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5637 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/CalendarProvider2( 5612): [IntentService] Release Lock
,D/CalendarProvider2( 5612): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  973): Killing 5474:com.lge.settings.easy/1000 (adj 15): empty #11
W/ResourcesManager( 5637): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup(  973): failed to open /acct/uid_1000/pid_5474/cgroup.procs: No such file or directory
,V/AudioFlinger(  283): thread 0xb56eb000 type 0 TID 1293 going to sleep
,V/AudioFlinger(  283): thread 0xb5735000 type 0 TID 1295 going to sleep
V/AudioFlinger(  283): thread 0xb5651000 type 0 TID 1292 going to sleep
D/AlertService( 5354): Beginning updateAlertNotification
,D/AlertService( 5354): No fired or scheduled alerts
I/NotificationManager( 5354): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(6) by com.android.calendar
,I/NotificationManager( 5354): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(13) by com.android.calendar
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager( 5354): com.android.calendar: cancel(14) by com.android.calendar
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager( 5354): com.android.calendar: cancel(15) by com.android.calendar
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  973): DHCPV4 succeeded on wlan0
I/NotificationManager( 5354): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5354): com.android.calendar: cancel(18) by com.android.calendar
D/LgDhcpStateMachineHelper(  973): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  973): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
I/NotificationManager( 5354): com.android.calendar: cancel(19) by com.android.calendar
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  973): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
I/NotificationManager( 5354): com.android.calendar: cancel(20) by com.android.calendar
V/LgDhcpStateMachineHelper(  973): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  973): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  973): bShouldSendDhcpAction Result: true
D/LGWifiP2pService(  973): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  973): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  973): RunningState
D/ConnectivityService(  973): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine(  973): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService(  973): ignoring duplicate network state non-change
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:10.254 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
,W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
,D/AlertService( 5354): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/ConnectivityService(  973): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  973): Adding iface wlan0 to network 100
E/WifiStateMachine(  973): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  973): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiHS20(  973): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:10.287 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1,840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:10.29 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:10.291 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 2
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 2
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
E/ConnectivityService(  973): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  973): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  973): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  973): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
,D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  973): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  973): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  973): Setting Dns servers for network 100 to [/192.168.1.1]
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  973): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  973): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  973): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  973): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  973):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): Connected
,D/ConnectivityService(  973):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  973):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  973):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  973):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  973): currentScore = 0, newScore = 20
D/ConnectivityService(  973):    accepting network in place of null
D/ConnectivityService(  973): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  973): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
D/WIFI    (  973): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  973):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  973): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  973): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  973): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
W/QCNEJ   ( 1840): |CORE| No family connected
D/Tethering(  973): MasterInitialState.processMessage what=3
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/TelephonyNetworkFactory-1( 1751): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  973): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=0
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/CSLegacyTypeTracker(  973): [e] list.add(nai) empty : false size: 1
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/ConnectivityService(  973): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/DSQN    (  973): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService(  973): validation of new default Network = false
D/ConnectivityService(  973): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  973): enableDataServiceNotify 
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = 1
D/DSQN    (  973): start dsqn bin
D/AlarmScheduler( 5354): No events found starting within 1 week.
,D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
V/NetworkPolicy(  973): [LG_RESTRICTED] checkMobilePolicy_type()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): [LWD] Start DNSResolver start to wait
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): [LWD] wait 500ms before dns check
D/ConnectivityService(  973): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  973):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  973):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  973): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
I/DSQN    ( 5681): DSQN samuel.seo ver 141203
I/ActivityManager(  973): Killing 5354:com.android.calendar/u0a13 (adj 15): empty #11
E/DSQN    ( 5681): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5681): created command queue thread
I/DSQN    ( 5681): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5681): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,W/libprocessgroup(  973): failed to open /acct/uid_10013/pid_5354/cgroup.procs: No such file or directory
I/Babel_SMS( 5637): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5637): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5637): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5637): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5637): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5637): MmsConfig.loadFromResources
E/Babel_SMS( 5637): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5637): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 5637): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5637): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5637): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5637): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 5637): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5637): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5637): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5637): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5637): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5637): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5637): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5637): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5637): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5637): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5637): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5637): found sensor: Motion Accel, handle=46
I/art     ( 5637): CheckpointMarkThreadRoots callback created = 0xb042d870
,W/Settings( 5637): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5637): startup - clean
I/Babel   ( 5637): deleted: false for 0
,I/art     ( 5637): CheckpointMarkThreadRoots callback created = 0xb042d840
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5412): MCCMNC not supported: null
W/AudioCapabilities( 5637): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5637): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5637): Unsupported mime audio/g726
V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 5637): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5637): Unsupported mime audio/wma-voice
D/WiFiOffLoadBroadcast( 5412): MCCMNC not supported: null
W/VideoCapabilities( 5637): Unsupported mime video/mjpg
W/VideoCapabilities( 5637): Unsupported mime video/theora
,V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5412): MCCMNC not supported: null
I/PCSuite ( 5454): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5454): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 5412): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 5637): Unsupported mime audio/evrc
W/AudioCapabilities( 5637): Unsupported mime audio/qcelp
D/WiFiOffLoadBroadcast( 5412): MCCMNC not supported: null
,W/VideoCapabilities( 5637): Unrecognized profile 2130706433 for video/avc
I/PCSuite ( 5454): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5454): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 5637): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5637): Unsupported mime audio/qcelp
W/AudioCapabilities( 5637): Unsupported mime audio/evrc
W/VideoCapabilities( 5637): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 5637): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5637): Unrecognized profile 2130706433 for video/avc
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): [LWD] DNSResolver start dns
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/VideoCapabilities( 5637): Unrecognized profile 2130706433 for video/avc
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
W/VideoCapabilities( 5637): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5637): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  973): Killing 5529:com.lge.lgdmsclient/1000 (adj 15): empty #11
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  973): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5681): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5681): restart monitoring
,D/LGDataListener(  276): argv[0]=dsqncommand
D/LGDataListener(  276): argv[1]=wlan0
D/LGDataListener(  276): argv[2]=1
D/LGDataListener(  276): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5681): dsqn report finish
D/DSQN    (  973): DSQM DsqnNotification wlan0  1
D/DSQN    (  973): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 21:14:10 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454534051016], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454534050997]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): Validated
D/ConnectivityService(  973): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  973): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  973):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  973):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  973):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  973): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  973): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  973):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  973):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  973): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  973): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
D/ConnectivityService(  973): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  973): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  973):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1751): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/libprocessgroup(  973): failed to open /acct/uid_1000/pid_5529/cgroup.procs: No such file or directory
D/WifiDataContinuityService(  973): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
,I/WifiServerServiceExt(  973): set CMD_CAPTIVE_CHECK_COMPLETED
I/vclib   ( 5637): onServiceConnected
W/Babel   ( 5637): Attempted to change video mute state without an active call.
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/NotificationManager( 5637): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  973): Process com.google.android.gms (pid 4045) has died
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-63 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:14:11.341 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NotificationManager( 1939): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/AlarmManager(  973): RTC_WAKEUP set : Alarm{14b2e324 type 0 when 1454534052250 com.android.vending} when 1454534052250
,D/Finsky  ( 5502): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  973): Process com.lge.bnr (pid 5577) has died
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  973): android: cancelAsUser(2) by android
,I/ActivityManager(  973): Start proc com.google.android.gms for service com.google.android.gms/.checkin.CheckinService: pid=5719 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 5719): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5719): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5719): VM with version 2.1.0 has multidex support
I/MultiDex( 5719): install
,I/MultiDex( 5719): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5719): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5719): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5719): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7e0191f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5719): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5719): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5719): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1734): callingUid 10006, callindPid: 1734
,D/libc-netbsd( 5502): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5502): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/MDM     ( 1734): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/libc-netbsd( 5502): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5502): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/LocationInitializer( 5719): Restart initialization of location
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 5502): propertyValue:false
D/libc-netbsd( 5502): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5502): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NativeLibraryUtils( 5719): Install completed successfully. count=14 extracted=0
,I/art     ( 5719): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5719): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/libc-netbsd( 5502): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5502): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/WifiInternetCheck(  973): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  973): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  973): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/LocSvc_java(  973): onReceive
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocSvc_java(  973): got connectivity action
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/LocSvc_java(  973): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  973): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  973): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  973): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  973): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  973): Sending msg: 5 arg1:0 arg2:1
I/ActivityManager(  973): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5763 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/art     ( 5719): CheckpointMarkThreadRoots callback created = 0xb042d570
I/System.out(  973): propertyValue:false
I/System.out(  973): propertyValue:false
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
,D/LocSvc_java(  973): NTP server returned: 1454534053374 (Wed Feb 03 22:14:13 GMT+01:00 2016) reference: 92770 certainty: 14 system time offset: -104
D/AlarmManagerService(  973): Setting time of day to sec=1454534053
W/AlarmManagerService(  973): Unable to set rtc to 1454534053: Invalid argument
D/LocSvc_java(  973): Sending msg: 10 arg1:0 arg2:1
I/art     ( 5719): CheckpointMarkThreadRoots callback created = 0xb042d560
,I/[SystemUI]Clock( 1375): onReceive = android.intent.action.TIME_SET
,I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
I/CalendarProvider2( 5612): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 5612): Scheduling check of next Alarm
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
,W/IcingInternalCorpora( 5719): getNumBytesRead when not calculated.
,I/ActivityManager(  973): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5785 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ActivityManager(  973): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
D/WeatherService( 2637): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 22:14:13
,I/[LGHome]LGDateChangeReceiver( 1878): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=3 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 1878): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 3
,D/WeatherService( 2637): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2637): 2 : This is isUpdating : false
D/WeatherService( 2637): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2637): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2637): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2637): 2 : Fixed theme : optimus
D/WeatherReflect( 2637): 2 : Map key string is -2
,I/ActivityManager(  973): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5802 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/[LGHome]LGCalendarIcon( 1878): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 3
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/lim     ( 2637): 2 : time = 22:14
,I/WeatherReflect( 2637): Model Name : LG-D722
D/WeatherTheme( 2637): 2 : exactly same view!
D/WeatherTheme( 2637): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2637): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 22:14:13
D/GpsLocationProvider(  973): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 5802): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5802): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5802): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 5785): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5785): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5785): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
E/GpsLocationProvider(  973): No APN found to select.
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  973): android: cancelAsUser(2) by android
E/ActivityThread( 5719): Failed to find provider info for com.android.contacts.metadata
,D/LgeGpsConstants(  973): Can't find 'ext_gps.conf'!!
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/SyncManager(  973): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 36278, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  973): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 126099, reason: UserStart
I/NotificationManager(  973): android: cancelAsUser(716319171) by android
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out(  973): propertyValue:false
I/qtaguid ( 5502): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5502): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5502): untagSocket(41) failed with errno -22
D/LgeGpsLocationProvider(  973): NTP server: europe.pool.ntp.org
,D/LgeGpsLocationProvider(  973): NTP server returned: 1454534053806 (Wed Feb 03 22:14:13 GMT+01:00 2016) reference: 93228 certainty: 22 system time offset: -22
D/Finsky  ( 5502): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/AppConfig( 5802): Total System Memory = 906309632
,I/GalleryUtils( 5802): Application Heap = 96 MB
,I/AppConfig( 5802): App Tier : NOT_DEF
,D/SystemHelper( 5802): region [EU], country [EU], operator [OPEN], sub-operator []
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/NotificationManager(  973): android: cancelAsUser(-1816247584) by android
,I/LGEmail ( 5785): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 5785): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/art     (  973): Explicit concurrent mark sweep GC freed 48165(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 3.992ms total 203.525ms
,I/MusicStore( 5763): Database version: 120
,I/ActivityManager(  973): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5841 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/NotificationManager(  973): android: cancelAsUser(-1597574061) by android
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 23.135ms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 27.995ms
I/NotificationManager(  973): android: cancelAsUser(2) by android
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 24.833ms
,E/Auth.Api.Credentials( 5719): [CredentialSyncAdapter] Unknown sync event.
,W/ResourcesManager( 5841): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5841): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NotificationManager(  973): android: cancelAsUser(-591465577) by android
E/ConnectivityChangeReceiver( 5719): Ignoring connectivity change
,I/NotificationManager(  973): android: cancelAsUser(-1816247584) by android
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
W/ContextImpl( 5763): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/MultiDex( 5841): VM with version 2.1.0 has multidex support
I/MultiDex( 5841): install
I/MultiDex( 5841): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  973): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=5867 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/qtaguid ( 5502): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5502): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5502): untagSocket(41) failed with errno -22
I/System.out(  973): propertyValue:false
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  973): propertyValue:false
,D/ConnectivityService(  973): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  973): dumpNetworkRequest
D/ConnectivityService(  973):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  973):     Requests:
D/ConnectivityService(  973):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  973):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  973):     Lingered:
D/ConnectivityService(  973): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  973): apparently satisfied.  currentScore=60
D/ConnectivityService(  973): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 5719): CM callback handler got msg 524290
V/WifiInternetCheck(  973): isHttpConnectionAvailable - We got a valid response : 204
,V/JNIHelp ( 5841): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NotificationManager(  973): android: cancelAsUser(-1597574061) by android
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5763): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5763): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ActivityThread( 5841): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5841): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@385a59d1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5841): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  973): Process com.android.providers.calendar (pid 5612) has died
,I/NotificationManager( 5841): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 5841): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ALBootInit( 5867): ====action==>android.intent.action.TIME_SET
D/ChimeraCfgMgr( 5841): Reading stored module config
,D/ALBootInit( 5867): Alarm ALBootInit: TIME_SET
D/Alarms  ( 5867): [setNextAlert] start
D/Alarms  ( 5867): [setNextAlert] (1)
,D/Alarms  ( 5867):  minTime  = 0
D/Alarms  ( 5867):  -- OK multi -- 0
E/jeny.kim( 5867): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 5867): [setNextAlert]setNextAlert temp_AlarmLinkText + 
W/ResourcesManager( 5763): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5763): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/CommonUtil( 5867): BUILD Operator: OPEN
,D/Alarms  ( 5867): broadcastToWidgetProvider : false
D/Alarms  ( 5867): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider(  973): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 5867): onReceive: android.intent.action.TIME_SET
D/ChimeraCfgMgr( 5841): Loading module com.google.android.gms.car from APK com.google.android.gms
V/DigitalAppWidgetProvider( 5867): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@54316bd
V/DigitalAppWidgetProvider( 5867): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@54316bd
D/QuickCoverProvider( 5867): onReceiver
,I/ActivityManager(  973): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=5896 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/JNIHelp ( 5763): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 94292583508; DSPS: 3187402; Offset : -2989392600
D/NativeLibraryUtils( 5841): Install completed successfully. count=14 extracted=0
,W/ResourcesManager( 5896): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ActivityThread( 5763): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5763): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c612d70: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5763): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 5763): GMSCore installation verified
,I/art     ( 5502): CheckpointMarkThreadRoots callback created = 0xb0567a00
,D/CalendarApplication( 5896): CalendarApplication.onCreate()
I/ConfigStore( 5763): Config Database version: 1
,I/art     ( 5502): CheckpointMarkThreadRoots callback created = 0xb05679e0
D/PreferenceKeysParser( 5896): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 5896): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1b5b3368, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@19eec381, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@100bc26, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1207e067, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@a641e14, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@54316bd, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1ac74b2, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@35a81c03, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3e6f0780, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@368f61b9, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@38e929fe, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3e86755f, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3d7d1bac, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1fbb6075, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@29a9e80a, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3c7087b, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@a764698, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2f6e8ef1, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@21067ad6, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@20b3b157, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2cd53444, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3d4c292d, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@13c76e62, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@31580bf3, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@71350b0, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3def2b29, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@8b20eae, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3cdd744f, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@27d4c7dc, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3aa650e5, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1b9467ba, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@29a7066b, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1d485c8, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@8f01661, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@25114586, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@172d9e47, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@36903674, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3db6b79d, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@132c3412, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@399bd7e3, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1fb445e0, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@184c3099
D/CAR.SERV,ICE( 5841): Connecting to CarCallService...
D/GeneralPreferenceUtils( 5896): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,D/Config  ( 5896): [init]
,I/Config  ( 5896): LGCalendar ver.4.40.17
I/Config  ( 5896): start check model
I/Config  ( 5896): start check native_ca
I/Config  ( 5896): Config Operator=OPEN, Country=EU
D/Config  ( 5896): [setDefaultValuesToPref]
D/Config  ( 5896): [parseProfiles]
D/ProfilesParser( 5896): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5896): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5896): [updateProfiletoCountryInfo]
,D/GeneralPreference( 5896): [checkAndMigrateOldPreference]
I/art     ( 5841): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5841): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/AgendaWidgetManager( 5896): [updateWidgets] 
,I/InitNotificationRingtoneService( 5896): Start InitializeAlertRingtoneService.onHandleIntent
I/NotificationManager(  973): android: cancelAsUser(-591465577) by android
,I/AlertUtils( 5896): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,D/CAR.SERVICE( 5841): com.google.android.projection.gearhead isn't installed.
I/art     ( 1967): Explicit concurrent mark sweep GC freed 2535(97KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.338ms total 33.834ms
,I/ActivityManager(  973): Process com.google.android.talk (pid 5637) has died
,I/AlertUtils( 5896): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
D/CAR.TEL.Service( 5841): Creating a new CarCallService.
I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
D/CAR.TEL.PhoneAdapter( 5841): Creating a new PhoneAdapter instance
I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5896): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5896): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 5896): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 5896): End InitializeAlertRingtoneService.onHandleIntent
W/ActivityManager(  973): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5841): setListener: com.google.android.gms.car.dn@2beffed4
W/ActivityManager(  973): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5841): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5841): Starting CarCallService with initial phone null
,W/HolidayIntentService( 5896): onHandleIntent
,D/MonthWidgetProvider( 5896): [onReceive]
D/CalendarWidgetProvider( 5896): [onReceive]
D/CalendarWidgetProvider( 5896): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5896): [onUpdateAndInitCalendarTime]
D/HolidayDataLoader( 5896): readJsonAsset : holiday.json
D/WeekWidgetProvider( 5896): [onReceive]
D/CalendarWidgetProvider( 5896): [onReceive]
D/CalendarWidgetProvider( 5896): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5896): [onUpdateAndInitCalendarTime]
,I/NotificationManager( 5841): com.google.android.gms: cancel(10436) by com.google.android.gms
D/WeatherAncestor( 2637): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 22:14:15
D/CAR.SERVICE( 5841): Package validated; name: com.android.vending
,D/UpdateThreadPoolManager( 2637): 2 : This is isUpdating : false
I/MediaRouter( 5763): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/Weather_cast( 2637): 2 : set auto-update time : 2/4 1:14
W/DriveInitializer( 5719): Awaiting to be initialized
D/WeatherAncestor( 2637): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 22:14:15
D/WeatherService( 2637): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
,W/DriveInitializer( 5719): Background init thread started
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5719): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,E/HolidayIntentService( 5896): onHandleIntent:holiday data empty
,I/ActivityManager(  973): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5930 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ActivityManager(  973): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2637): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2637): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2637): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,V/MusicLeanback( 5763): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,V/Finsky  ( 5502): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/NotificationManager( 5502): com.android.vending: cancel(10436) by com.android.vending
I/NetworkMonitor( 5763): type=WIFI subType= reason=null isConnected=true
,D/TimeService( 5930): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454534055822
D/        ( 5930): TimeServiceNative: User Time to be set is 1454534055823
D/QC-time-services( 5930): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5930): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5930): Lib:time_genoff_operation: pargs->ts_val = 1454534055823
D/QC-time-services( 5930): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  344): Daemon: Connection accepted:time_genoff
D/QC-time-services(  344): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454534055823
D/QC-time-services(  344): Daemon:genoff_opr: Base = 2, val = 1454534055823, operation = 0
D/QC-time-services(  344): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/17/70 1:15:46
D/QC-time-services(  344): Daemon:Value read from RTC seconds = 14433346000
D/QC-time-services(  344): Daemon:new time 1454534055823 
D/QC-time-services(  344): Daemon: delta 1440100709823 genoff 1440100709823 
D/QC-time-services(  344): Daemon:genoff_persistent_update: Writing genoff = 1440100709823 to memory
D/QC-time-services(  344): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  344): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  344): Updating the TOD offset
D/QC-time-services(  344): Daemon:genoff_persistent_update: Writing genoff = 1440100709823 to memory
D/QC-time-services(  344): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  344): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  344): Daemon:Update to modem bit set
D/QC-time-services(  344): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 5930): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  344): Daemon: Base = 2, Value being sent to MODEM = 1124135909823
E/QC-time-services(  344): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  344): Daemon: Time-services: Waiting to acceptconnection
W/DriveInitializer( 5719): Background init thread ended
,I/ActivityManager(  973): Process com.android.settings (pid 5412) has died
,I/CheckinService( 5719): Checkin interval check for package: unspecified last checkin: 1454531546363 min interval config: 0 actual interval: 2509602
,I/NetworkMonitor( 5763): type=WIFI subType= reason=null isConnected=true
,I/NotificationManager( 5719): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager(  973): android: cancelAsUser(353845882) by android
I/GHttpClientFactory( 5763): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/eas_req ( 5785): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/GoogleURLConnFactory( 5763): Using platform SSLCertificateSocketFactory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  973): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5971 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  973): Process com.lge.qremote (pid 5058) has died
,D/UEI.SmartControl( 4692): Service.onUnbind: IControl
D/UEI.SmartControl( 4692): Service.onDestroy
D/ChimeraCfgMgr( 5719): Reading stored module config
I/PhoneApp( 1751): onTrimMemory: 10
I/PhoneApp( 1751): trim memory
,D/UEI.SmartControl( 4692): Shutdown IRRCPlayer... 
W/irrc_jni( 4692): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4692): ~IrrcClient ++ 
D/irrcClient( 4692): ~IrrcClient -- 
W/irrc_jni( 4692): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4692): Blaster closed
D/UEI.SmartControl( 4692): Blaster closed
D/UEI.SmartControl( 4692): Shut down QS...
D/UEI.SmartControl( 4692): Stopped file observer...
I/UEI.SmartControl( 4692): QS lib stop result = true
D/UEI.SmartControl( 4692): QS shutdown complete
I/art     (  973): Explicit concurrent mark sweep GC freed 20973(997KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.924ms total 195.655ms
I/BackgroundMemoryTrimmer( 1939): Trimming objects from memory, since app is in the background.
,D/ChimeraCfgMgr( 5719): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5719): Loading module APK com.google.android.play.games
I/NotificationManager(  973): android: cancelAsUser(353845882) by android
I/jxcore-log( 5252): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5252): 
,I/NotificationManager( 5763): com.google.android.music: cancel(1061) by com.google.android.music
,I/HubEmail( 5785): JNI_OnLoad()
I/HubEmail( 5785): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5785): registerNatives()
I/HubEmail( 5785): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5785): registerNativeMethods()
I/HubEmail( 5785): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 5785): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 5785): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 5971): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 5971): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 5971): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 5971): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 5971): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 5971): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 5971): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 5971): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  973): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=5997 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 5971): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 5971): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 5971): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 5971): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LGDMClient( 5971): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 5971): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/NotificationManager(  973): android: cancelAsUser(2) by android
,I/ActivityManager(  973): Process com.lge.clock (pid 5867) has died
,I/AppUp4:AppBoxCP( 5997): onCreate
,W/AppUp4:DB( 5997):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 5997):  setFingerPrint start
,I/AppUp4:DB( 5997):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5997):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5997):  SDK version = 0
I/AppUp4:DB( 5997):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5997): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 5997): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 5997): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 5997): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 5997): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 5997): onReceive
I/AppUp4:CustModeStarterReceiver( 5997): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 5997): Context : android.app.ReceiverRestrictedContext@a641e14
D/AppUp4:CustFacade( 5997): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5997): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5997): begin check event
I/AppUp4:CustModeStarterReceiver( 5997): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 5997): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 5997): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 5997): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 5997): handleAsyncCustNotification do not startCustService
I/qtaguid ( 5502): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5502): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5502): untagSocket(41) failed with errno -22
,I/LgeMiscReceiver( 3112): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3112): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3112): networkInfo.isConnected() = true
,D/PhoneState( 3112): setPdpRejectCasuse : false
I/ActivityManager(  973): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6017 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  973): Process com.android.calendar (pid 5896) has died
,D/PhoneMonitor( 6017): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6017): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6017): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 5719): Checkin interval check for package: unspecified last checkin: 1454531546363 min interval config: 0 actual interval: 2510778
,V/DownloadManager( 3135): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/CheckinService( 5719): Disabling old GoogleServicesFramework version
,D/PhoneMonitor( 6017): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6017): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6017): [parse] Load xml
V/DownloadManager( 3135): DownloadService onCreate
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/TelephonyAutoProfiling( 6017): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6017): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,I/DownloadManager( 3135): in removeSpuriousFiles
V/DownloadManager( 3135): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/ActivityManager(  973): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6041 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@1fb445e0 on behalf of 3135
,I/NotificationManager( 3135): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3135): in trimDatabase
V/DownloadManager( 3135): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/PhoneMonitor( 6017): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3135): DownloadService onStartCommand
V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@132a0f3f on behalf of 3135
,V/DownloadManager( 3135): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@347e00c on behalf of 3135
W/ResourcesManager( 5502): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5502): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5502): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/DrmBroadcastReceiver( 6041): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6041): 1  network is available. Sync DRM Time with NTP
,D/WeatherAncestor( 2637): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:14:17
D/UpdateThreadPoolManager( 2637): 2 : This is isUpdating : false
D/WeatherAncestor( 2637): connectivity changed - connection : true
,D/Weather_cast( 2637): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2637): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:14:17
D/WeatherService( 2637): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
V/DrmService( 6041): Service onCreate
D/DrmService( 6041): Received new request = 2
I/DrmSntpClient( 6041): Start Sync process
D/DrmSntpClient( 6041): Server : 0
D/libc-netbsd( 6041): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6041): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6041): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6041): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  276): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
,I/art     ( 5719): Explicit concurrent mark sweep GC freed 25524(1882KB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 12MB/20MB, paused 1.809ms total 136.760ms
,I/ActivityManager(  973): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6061 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  973): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2637): 2 : Utils getTopActivity com.lge.launcher2 / true
D/Finsky  ( 5502): [1] DailyHygiene.access$600: Logging device features
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 6041): propertyValue:false
D/WeatherService( 2637): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2637): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,V/DownloadManager( 3135): DownloadService onDestroy
V/AlarmManager(  973): RTC_WAKEUP set : Alarm{1ac08f01 type 0 when 1454534057437 com.android.vending} when 1454534057437
I/LGDrmClient( 6041): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  289): eDRM_SetDRMTime +++
I/CheckinService( 5719): Checking schedule, now: 1454534057471 next: 1454531576328
I/CheckinService( 5719): active receiver: enabled
,I/LGDRM   (  289): [DRM] SET TIME : YR=2016, MON=2, DAY=3
I/LGDRM   (  289): [DRM] SET TIME : HR=21, MIN=14, SEC=17
,I/CheckinService( 5719): Preparing to send checkin request
,V/ILGDrmService(  289): eDRM_SetDRMTime ---
I/DrmSntpClient( 6041): Synched
D/DrmService( 6041): Completed !! request = 2
D/DrmService( 6041): Request count = 0
V/DrmService( 6041): Service onDestroy
I/ActivityManager(  973): Killing 4692:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/EventLogService( 5719): Accumulating logs since 1454533463748
,W/ResourcesManager( 6061): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/jxcore-log( 5252): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5252): 
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 31295(2MB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 13MB/22MB, paused 1.142ms total 110.978ms
D/DeviceConnectionService( 1734): client connected with version: 8296000
W/libprocessgroup(  973): failed to open /acct/uid_10089/pid_4692/cgroup.procs: No such file or directory
,D/Finsky  ( 5502): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5502): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  973): Killing 5454:com.lge.sync/1000 (adj 15): empty #11
I/jxcore-log( 5252): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5252): 
,I/jxcore-log( 5252): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5252): 
,W/libprocessgroup(  973): failed to open /acct/uid_1000/pid_5454/cgroup.procs: No such file or directory
,I/Babel_SMS( 6061): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6061): MmsConfig.loadMmsSettings
I/Babel_SMS( 6061): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6061): MmsConfig.loadFromDatabase
,I/jxcore-log( 5252): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5252): 
,E/Babel_SMS( 6061): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6061): MmsConfig.loadFromResources
E/Babel_SMS( 6061): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6061): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/jxcore-log( 5252): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5252): 
,I/jxcore-log( 5252): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5252): 
,I/jxcore-log( 5252): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5252): 
,I/ActivityManager(  973): Process com.google.android.music:main (pid 5763) has died
,D/SensorManager( 6061): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6061): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6061): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6061): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6061): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6061): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6061): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6061): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6061): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6061): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6061): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6061): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6061): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6061): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6061): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6061): found sensor: Motion Accel, handle=46
,I/art     ( 6061): CheckpointMarkThreadRoots callback created = 0xb042d890
,I/CheckinRequestBuilder( 5719): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 5719): Failed to find provider info for com.google.android.wearable.settings
W/Settings( 6061): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6061): startup - clean
,I/art     ( 6061): CheckpointMarkThreadRoots callback created = 0xb042d870
I/Babel   ( 6061): deleted: false for 0
,I/ActivityManager(  973): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6092 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6061): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6061): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6061): Unsupported mime audio/g726
W/AudioCapabilities( 6061): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6061): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6061): Unsupported mime video/mjpg
W/VideoCapabilities( 6061): Unsupported mime video/theora
,W/AudioCapabilities( 6061): Unsupported mime audio/evrc
W/AudioCapabilities( 6061): Unsupported mime audio/qcelp
W/VideoCapabilities( 6061): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6061): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6061): Unsupported mime audio/qcelp
W/AudioCapabilities( 6061): Unsupported mime audio/evrc
W/VideoCapabilities( 6061): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6061): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6061): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6061): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6061): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6061): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  973): Process com.lge.email (pid 5785) has died
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{260a5b73 type 2 when 97923 com.android.providers.calendar} when 97923
I/vclib   ( 6061): onServiceConnected
W/Babel   ( 6061): Attempted to change video mute state without an active call.
,I/NotificationManager( 6061): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  276): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 6061): propertyValue:false
I/Babel   ( 6061): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  973): Process com.android.gallery3d (pid 5802) has died
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6092): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6092): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6092): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6092): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6092): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6092):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6092):   adb logcat -s GAv4
,I/ActivityManager(  973): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6120 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/GAv4    ( 6092): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 6120): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6120): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAv4    ( 6092): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6092): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/MultiDex( 6120): VM with version 2.1.0 has multidex support
I/MultiDex( 6120): install
I/MultiDex( 6120): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6120): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6120): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6120): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@385a59d1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6120): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6120): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6120): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 6120): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6120): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/NativeLibraryUtils( 6120): Install completed successfully. count=14 extracted=0
,I/WebViewFactory( 6092): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/WVCdm   (  283): Instantiating CDM.
,I/WVCdm   (  283): CdmEngine::OpenSession
I/WVCdm   (  283): Level3 Library Dec 11 2014 16:13:16
I/LibraryLoader( 6092): Time to load native libraries: 2 ms (timestamps 8693-8695)
I/LibraryLoader( 6092): Expected native library version number "",actual native library version number ""
,W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  283): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  283): L1 library not specified. Falling Back to L3
,V/WebViewChromiumFactoryProvider( 6092): Binding Chromium to main looper Looper (main, tid 1) {17545941}
,I/LibraryLoader( 6092): Expected native library version number "",actual native library version number ""
I/chromium( 6092): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6092): Initializing chromium process, singleProcess=true
W/art     ( 6092): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6092): ApplicationContext is null in ApplicationStatus
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
W/chromium( 6092): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/WVCdm   (  283): PrepareKeyRequest: nonce=1660203901
E/libEGL  ( 6092): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6092): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6092): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6092): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6092): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6092): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6092): Remote Branch: 
I/Adreno-EGL( 6092): Local Patches: 
I/Adreno-EGL( 6092): Reconstruct Branch: 
V/AudioPolicyService(  283): registerClient() client 0xb3ece6e0, uid 10079
,W/AudioManagerAndroid( 6092): Requires BLUETOOTH permission
I/NSApplication( 6092): Starting up...
,I/ActivityManager(  973): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6175 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6120): CheckpointMarkThreadRoots callback created = 0xb042d590
,I/art     (  309): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 384us total 26.953ms
I/art     (  309): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.845ms
I/art     ( 6120): CheckpointMarkThreadRoots callback created = 0xb042d570
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 22.844ms
,I/WVCdm   (  283): CdmEngine::OpenSession
,I/ActivityManager(  973): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6196 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  973): Killing 5930:com.qualcomm.timeservice/1000 (adj 15): empty #11
W/libprocessgroup(  973): failed to open /acct/uid_1000/pid_5930/cgroup.procs: No such file or directory
,W/ResourcesManager( 6196): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  973): Killing 5971:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_1000/pid_5971/cgroup.procs: No such file or directory
,I/art     ( 1967): Explicit concurrent mark sweep GC freed 2689(108KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 381us total 24.506ms
,I/iu.SyncManager( 5719): SYNC; picasa accounts
,D/NetworkLogImpl( 5719): Loaded NetworkSpeedPredictor
I/iu.Environment( 5719): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/CAR.SERVICE( 5841): mConnectedToCar = false, abort
,E/ActivityThread( 5841): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3389643c that was originally bound here
E/ActivityThread( 5841): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3389643c that was originally bound here
E/ActivityThread( 5841): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5841): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5841): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5841): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5841): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5841): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5841): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5841): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5841): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5841): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5841): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5841): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5841): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5841): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5841): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5841): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5841): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5841): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5841): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5841): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5841): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5841): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5841): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 5841): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2047cc27 that was originally bound here
E/ActivityThread( 5841): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2047cc27 that was originally bound here
E/ActivityThread( 5841): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5841): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5841): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5841): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5841): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5841): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5841): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5841): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5841): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5841): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5841): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5841): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5841): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5841): 	at android.app.ActivityThread.acce,ss$1900(ActivityThread.java:155)
E/ActivityThread( 5841): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5841): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5841): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5841): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5841): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5841): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5841): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5841): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/iu.UploadsManager( 5719): num queued entries: 0
I/iu.UploadsManager( 5719): num updated entries: 0
I/iu.SyncManager( 5719): NEXT; no task
W/ActivityManager(  973): Unbind failed: could not find connection for android.os.BinderProxy@342295cb
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
E/MDM     ( 1734): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5719): Restart initialization of location
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 1734): propertyValue:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/GCM     ( 1734): GCM config loaded
I/art     (  973): Explicit concurrent mark sweep GC freed 20996(1007KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.494ms total 150.874ms
,I/ActivityManager(  973): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6245 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/DigitalAppWidgetProvider( 6245): onReceive: android.intent.action.ALARM_CHANGED
,I/ActivityManager(  973): Killing 5997:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/WVCdm   (  283): CdmEngine::CloseSession
,W/libprocessgroup(  973): failed to open /acct/uid_10011/pid_5997/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2637): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 22:14:21
D/UpdateThreadPoolManager( 2637): 2 : This is isUpdating : false
D/Weather_cast( 2637): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2637): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 22:14:21
D/WeatherService( 2637): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  973): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2637): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2637): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2637): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/Finsky  ( 5502): [645] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager(  973): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6264 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WVCdm   (  283): PrepareKeyRequest: nonce=3109283636
I/NotificationManager(  973): android: cancelAsUser(2) by android
,W/ResourcesManager( 6264): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/libc-netbsd( 5502): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5502): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5502): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5502): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/CalendarProvider2( 6264): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@214bb45a
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 5502): propertyValue:false
D/CalendarProvider2( 6264): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6264): Created com.android.providers.calendar.CalendarAlarmManager@1207e067(com.android.providers.calendar.CalendarProvider2@214bb45a)
,D/CalendarProviderBroadcastReceiver( 6264): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6264): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6264): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6264): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/CalendarProvider2( 6264): [getOrCreateCalendarAlarmManager]
D/LocationInitializer( 5719): Restart initialization of location
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
E/MDM     ( 1734): [118] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
D/CalendarProvider2( 6264): [IntentService] Release Lock
,D/CalendarProvider2( 6264): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  973): Killing 6017:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10038/pid_6017/cgroup.procs: No such file or directory
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): L3 Terminate.
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/dex2oat ( 6304): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6304): dex2oat took 104.759ms (threads: 4)
,I/Adreno-EGL( 6120): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6120): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6120): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6120): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6120): Remote Branch: 
I/Adreno-EGL( 6120): Local Patches: 
I/Adreno-EGL( 6120): Reconstruct Branch: 
,I/Adreno-EGL( 6120): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6120): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6120): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6120): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6120): Remote Branch: 
I/Adreno-EGL( 6120): Local Patches: 
I/Adreno-EGL( 6120): Reconstruct Branch: 
,I/Adreno-EGL( 6120): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6120): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6120): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6120): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6120): Remote Branch: 
I/Adreno-EGL( 6120): Local Patches: 
I/Adreno-EGL( 6120): Reconstruct Branch: 
,I/ActivityManager(  973): Process com.google.android.apps.magazines (pid 6092) has died
,I/CheckinRequestBuilder( 5719): Classify the device as Phone.
,D/libc-netbsd( 5719): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5719): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5719): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5719): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 5719): propertyValue:false
D/libc-netbsd( 5719): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5719): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5719): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5719): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5719): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5719): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5719): Sending checkin request (9748 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinRequestBuilder( 5719): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5719): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5719): Classify the device as Phone.
,I/CheckinTask( 5719): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5719): Checking schedule, now: 1454534065544 next: 1455061314537
I/CheckinService( 5719): active receiver: disabled
,D/CheckinService( 5719): Recording last checkin time for package unspecified as 1454534065576
I/ActivityManager(  973): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6333 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6333): Register our PhoneStateListener
,V/SetupWizard( 6333): Connected to Gservices successfully
,D/PhoneMonitor( 6333): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6333): [loadFeatureFromXml] *** start feature loading from xml
D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/TelephonyAutoProfiling( 6333): [parse] Load xml
,V/TelephonyAutoProfiling( 6333): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6333): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6333): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  973): Killing 5841:com.google.android.gms:car/u0a6 (adj 15): empty #11
,I/ActivityManager(  973): Killing 6041:com.lge.drmservice/u0a51 (adj 15): empty #12
,W/libprocessgroup(  973): failed to open /acct/uid_10006/pid_5841/cgroup.procs: No such file or directory
,W/libprocessgroup(  973): failed to open /acct/uid_10051/pid_6041/cgroup.procs: No such file or directory
I/jxcore-log( 5252): Test app app.js loaded
I/jxcore-log( 5252): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5252): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5252): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5252): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5252): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5252): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5252): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5252): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5252): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5252): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5252): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187967b9 added. We now have 1 listener(s)
,D/BluetoothAdapterService(900209667)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f6e8ef1
I/jxcore-log( 5252): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5252): 
I/chromium( 5252): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  973): Reconfiguring input devices.  changes=0x00000010
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  973): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6376 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/administrator(  973): Handling package changes for user 0
,I/NotificationManager( 6061): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6061): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6061): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 6376): onCreate
W/AppUp4:DB( 6376):  [AppBoxDatabaseHelper] construct
,V/JNIHelp ( 6061): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AppUp4:DB( 6376):  setFingerPrint start
,I/AppUp4:DB( 6376):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6376):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6376):  SDK version = 0
I/AppUp4:DB( 6376):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6376): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 6376): onReceive
I/AppUp4:CustModeStarterReceiver( 6376): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6376): Context : android.app.ReceiverRestrictedContext@19eec381
D/AppUp4:CustFacade( 6376): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6376): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6376): begin check event
I/AppUp4:CustModeStarterReceiver( 6376): Event For Nothing, skip.
W/System  ( 6061): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6061): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  973): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6399 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
,W/ResourcesManager( 6399): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6399): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6399): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/NotificationService(  973): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  973): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  973): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  973): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  973): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  973): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@23b7230c
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager(  973): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  973): Process com.google.android.apps.plus (pid 6196) has died
,I/AppConfig( 6399): Total System Memory = 906309632
I/GalleryUtils( 6399): Application Heap = 96 MB
,W/ResourceType(  973): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/AppConfig( 6399): App Tier : NOT_DEF
D/SystemHelper( 6399): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  973): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6419 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  973): Process com.lge.clock (pid 6245) has died
,I/ActivityManager(  973): Process com.android.chrome (pid 6175) has died
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 6419): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6419): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6419): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6419): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6419): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LocationProviderProxy(  973): applying state to connected service
,I/SystemConfig( 6419): BUILD Country: EU
I/SystemConfig( 6419): BUILD Operator: OPEN
,I/ActivityManager(  973): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6445 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6419): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6419): existFile = false
I/SystemConfig( 6419): canReadFile = false
I/SystemConfig( 6419): systemFeature RCS result false
D/SystemConfig( 6419): refreshRcsSupport() :false
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/LockScreenSettings( 6445): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/LockScreenSettings( 6445): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6445): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6445): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6445): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6445): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  973): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6462 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6462): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  973): Killing 6264:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 91 ms] updated apps [took 91 ms] 
,W/libprocessgroup(  973): failed to open /acct/uid_10014/pid_6264/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 5719): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5719): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5719): Storage manager: low false usage 1.69MB avail 2.37GB capacity 4.06GB
,I/art     (  973): Explicit concurrent mark sweep GC freed 25603(1353KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.251ms total 141.347ms
,I/ActivityManager(  973): Process com.android.gallery3d (pid 6399) has died
,I/Icing   ( 5719): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 5719): Internal init done: storage state 0
,I/Icing   ( 5719): Post-init done
,I/Icing   ( 5719): updateResources: need to parse f{com.google.android.gms}
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  973): RTC_WAKEUP set : Alarm{1fae352b type 0 when 1454534070935 com.android.vending} when 1454534070935
,W/ContextImpl( 3402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 5502): [635] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5502): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/Icing   ( 5719): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 5719): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5719): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/MusicWidget( 2559): mDelayedStopHandler : unbind
,I/MusicBrowser( 2647): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2647): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2647): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2647): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2647): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2647): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2647): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2647): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  973):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3d4c292dcom.lge.music.MediaPlaybackService$6@13c76e62
,D/MusicBrowser( 2647): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2647): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2647): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2647): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2647): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@3e6f0780
I/MusicBrowser( 2647): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2647): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2647): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2647): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2647): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2647): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2647): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2647): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2647): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2647): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2647): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2647): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2647): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2647): reset
,V/MediaPlayer[Native]( 2647): setListener
,V/MediaPlayer[Native]( 2647): disconnect
V/MediaPlayer[Native]( 2647): destructor
V/AudioFlinger(  283): releasing 18 from 2647 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/MediaPlayer[Native]( 2647): disconnect
D/MusicBrowser( 2647): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2647): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2647): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2647): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2647): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2647): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2647): [SmartShareManagerClient] unregisterListener: 827853811
W/SmartShareClient( 2647): [SmartShareManagerClient] unregisterListener invalid listener: 827853811
I/SmartShareClient( 2647): [SmartShareManagerClient] terminate service: 2647/MediaPlaybackService/16825382
E/HomeCloudIF( 2647): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2647): [SmartShareManagerClient] unbindService context:android.app.Application@71350b0
V/CloudHub( 2647): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2647): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2647): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2647): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2647): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  973): Killing 6333:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/CloudHub( 2647): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
,W/libprocessgroup(  973): failed to open /acct/uid_10038/pid_6333/cgroup.procs: No such file or directory
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 114293256262; DSPS: 3842783; Offset : -2989361861
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/CheckinService( 5719): Done disabling old GoogleServicesFramework version
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{1ba1ed88 type 2 when 122968 android} when 122968
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/CloudHub( 2647): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19992
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 134294006619; DSPS: 4498168; Offset : -2989374105
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{1981c321 type 2 when 134351 com.google.android.gms} when 134351
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1734): Vacuum at: now=1454534095154 tag=VacuumService
W/InstanceID/Rpc( 5719): Found 10006
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
,I/[SystemUI]Clock( 1375): called onTimeUpdated()
I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
,I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/PowerManagerServiceEx(  973): acquireWakeLockInternal: lock=312647660, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=973
,D/WeatherService( 2637): 2 : TimeTick Intent has been received, Time(hour:min:sec) 22:15:0
,D/WeatherService( 2637): 2 : TimeTick Intent And Screen On
D/WeatherService( 2637): 2 : SDK version : 21
W/ActivityManager(  973): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2637): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2637): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2637): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2637): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2637): 2 : This is isUpdating : false
D/WeatherService( 2637): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2637): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2637): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2637): 2 : Fixed theme : optimus
D/WeatherReflect( 2637): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/lim     ( 2637): 2 : time = 22:15
I/WeatherReflect( 2637): Model Name : LG-D722
D/WeatherTheme( 2637): 2 : Different view - status_min_formatted : 14 != 15
D/WeatherTheme( 2637): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2637): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2637): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2637): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2637): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2637): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2637): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2637): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2637): forecast size is 0
,D/Theme   ( 2637): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2637): EnableTheme(home): com.lge.launcher2.theme.optimus
,D/Theme   ( 2637): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2637): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2637): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2637): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2637): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2637): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2637): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2637): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2637): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2637): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2637): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2637): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2637): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2637): url is : null
D/Theme   ( 2637): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2637): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2637): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2637): 2 : update view, appWidgetId: 2
D/WeatherService( 2637): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 22:15:0
,D/PowerManagerServiceEx(  973): releaseWakeLockInternal: lock=312647660 [*alarm*], flags=0x0
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  973): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6626 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 6626): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6626): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@19eec381
I/ActivityManager(  973): Killing 6061:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  973): failed to open /acct/uid_10061/pid_6061/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/CloudHub( 2647): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2647): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-67 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:15:05.451 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-63 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 22:15:08.463 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  973): ALS enabled for SRE
D/PowerManagerServiceEx(  973): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (30529 ms ago)
,D/qdlights(  973): set_light_backlight: 254
,D/qdlights(  973): set_light_backlight: 251
,D/qdlights(  973): set_light_backlight: 247
,D/qdlights(  973): set_light_backlight: 244
,D/qdlights(  973): set_light_backlight: 241
,D/qdlights(  973): set_light_backlight: 237
,D/qdlights(  973): set_light_backlight: 234
,D/qdlights(  973): set_light_backlight: 231
,D/qdlights(  973): set_light_backlight: 227
,D/qdlights(  973): set_light_backlight: 224
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  973): set_light_backlight: 221
,D/qdlights(  973): set_light_backlight: 217
,D/qdlights(  973): set_light_backlight: 214
,D/qdlights(  973): set_light_backlight: 211
,D/qdlights(  973): set_light_backlight: 207
,D/qdlights(  973): set_light_backlight: 204
,D/qdlights(  973): set_light_backlight: 201
,D/qdlights(  973): set_light_backlight: 197
,D/qdlights(  973): set_light_backlight: 194
,D/qdlights(  973): set_light_backlight: 191
,D/qdlights(  973): set_light_backlight: 187
,D/qdlights(  973): set_light_backlight: 184
,D/qdlights(  973): set_light_backlight: 181
,D/qdlights(  973): set_light_backlight: 177
,D/qdlights(  973): set_light_backlight: 174
,D/qdlights(  973): set_light_backlight: 171
,D/qdlights(  973): set_light_backlight: 167
,D/qdlights(  973): set_light_backlight: 164
,D/qdlights(  973): set_light_backlight: 161
,D/qdlights(  973): set_light_backlight: 157
,D/qdlights(  973): set_light_backlight: 154
,D/qdlights(  973): set_light_backlight: 151
,D/qdlights(  973): set_light_backlight: 147
,D/qdlights(  973): set_light_backlight: 144
,D/qdlights(  973): set_light_backlight: 141
,D/qdlights(  973): set_light_backlight: 137
,D/qdlights(  973): set_light_backlight: 134
,D/qdlights(  973): set_light_backlight: 131
,D/qdlights(  973): set_light_backlight: 127
,D/qdlights(  973): set_light_backlight: 124
,D/qdlights(  973): set_light_backlight: 121
,D/qdlights(  973): set_light_backlight: 117
,D/qdlights(  973): set_light_backlight: 114
,D/qdlights(  973): set_light_backlight: 111
,D/qdlights(  973): set_light_backlight: 107
,D/qdlights(  973): set_light_backlight: 104
,D/qdlights(  973): set_light_backlight: 101
,D/qdlights(  973): set_light_backlight: 97
,D/qdlights(  973): set_light_backlight: 94
,D/qdlights(  973): set_light_backlight: 91
,D/qdlights(  973): set_light_backlight: 87
,D/qdlights(  973): set_light_backlight: 84
,D/qdlights(  973): set_light_backlight: 81
,D/qdlights(  973): set_light_backlight: 77
,D/qdlights(  973): set_light_backlight: 74
,D/qdlights(  973): set_light_backlight: 71
,D/qdlights(  973): set_light_backlight: 67
,D/qdlights(  973): set_light_backlight: 64
,D/qdlights(  973): set_light_backlight: 61
,D/qdlights(  973): set_light_backlight: 57
,D/qdlights(  973): set_light_backlight: 54
,D/qdlights(  973): set_light_backlight: 51
,D/qdlights(  973): set_light_backlight: 47
,D/qdlights(  973): set_light_backlight: 44
,D/qdlights(  973): set_light_backlight: 41
,D/qdlights(  973): set_light_backlight: 37
,D/qdlights(  973): set_light_backlight: 34
,D/qdlights(  973): set_light_backlight: 31
,D/qdlights(  973): set_light_backlight: 27
,D/qdlights(  973): set_light_backlight: 24
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  973): set_light_backlight: 21
,D/qdlights(  973): set_light_backlight: 17
,D/qdlights(  973): set_light_backlight: 14
,D/qdlights(  973): set_light_backlight: 11
,D/qdlights(  973): set_light_backlight: 10
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{129a851e type 2 when 152982 android} when 152982
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,E/ActivityThread( 5719): Failed to find provider info for com.android.contacts.metadata
D/SyncManager(  973): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 126099, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  973): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 219375, reason: UserStart
I/NotificationManager(  973): android: cancelAsUser(716319171) by android
D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 154294746455; DSPS: 5153552; Offset : -2989368410
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  973): ALS enabled for SRE
D/PowerManagerServiceEx(  973): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (37523 ms ago)
,I/PowerManagerService(  973): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  973): ALS enabled for SRE
D/PowerManagerServiceEx(  973): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (37538 ms ago)
,W/ContextImpl(  973): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  973): Sleeping (uid 1000)...
,D/LPWGController(  973): [updateScreenState] screen on = false
D/LPWGController(  973): disable proximity sensor
D/LPWGController(  973): enable proximity sensor
I/SensorManager(  973): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@33cabf1b] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  973): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  973): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  973): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  973): activate: handle is 48, enable
V/sensors_hal_Ctx(  973): activate sensors is 1400000000000
D/sensors_hal_Thresh(  973): enable: handle=48
I/sensors_hal_SAM(  973): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  973): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  973): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  973): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  973): enable: Received response: 0
D/PowerManagerServiceEx(  973): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (37585 ms ago)
I/Adreno-EGL(  973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  973): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  973): Build Date: 03/02/15 Mon
I/Adreno-EGL(  973): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  973): Remote Branch: 
I/Adreno-EGL(  973): Local Patches: 
I/Adreno-EGL(  973): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (986 us)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Sensors (  423): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  973): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  973): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  973): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  973): processInd: handle 48, count=1
V/sensors_hal_Thresh(  973): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  973): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  973): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  973): poll: count: 256
I/sensors_hal_Ctx(  973): poll: released wakelock sensor_ind
D/sensors_hal_Util(  973): waitForResponse: timeout=0
D/LPWGController(  973): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  973): current mode = 1  value = 1 1
I/LPWGController(  973): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  973): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  973): set_light_backlight: 0
,I/SensorManager(  973): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  973): activate: handle is 46, disable
V/sensors_hal_Ctx(  973): activate sensors is 1000000000000
D/sensors_hal_LP2(  973): enable: handle=46
D/sensors_hal_LP2(  973): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  973): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  973): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  973): Display changed displayId=0
V/sensors_hal_SAM(  973): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  973): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1751): Display #0 changed.
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  973): Excessive delay in setPowerMode(): 193ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  973): Got set_interactive hint
,D/KeyguardViewMediator( 1375): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
D/KeyguardViewMediator( 1375): notifyScreenOffLocked
D/WifiServerServiceExt(  973): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=on, calling pid 973
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
,V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  283): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
D/KeyguardViewMediator( 1375): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1375): handleNotifyScreenOff
I/WifiServerServiceExt(  973): set CMD_KT_SCAN_INTERVAL
D/ScreenTurnOffBySensor( 1375): unregisterProximitySensor
,D/StatusBarWindowView( 1375): onScreenTurnedOff why = 3
D/GpsLocationProvider(  973): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
,I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
D/LNfcService( 1787): action : android.intent.action.SCREEN_ON
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1804): lockStatus = 0
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1804): updateLightsLocked : turn off led
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/Ulp_jni (  973): JNI:system_update. Event-0
D/LEDHandler( 1804): RESTART MSG
D/NfcServiceNXP( 1787): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1787): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1787): isRequireNfcCRouting() return true
D/LNfcService( 1787): isHCERoutingtoHost() return : true
D/NfcService( 1787): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): newParams.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): screenState= 3
D/NfcService( 1787): Discovery configuration equal, not updating.
D/SplitWindow(  973): check instance of lgWin Window{39e419f6 u0 SearchPanel}
,D/InputDispatcher(  973): Window went away: Window{1c963f44 u0 SearchPanel}
,I/[SystemUI]Clock( 1375): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2637): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 22:15:19
D/WeatherService( 2637): 2 : ACTION screen on
D/WeatherService( 2637): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2637): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherService( 2637): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 22:15:19
D/AppCleanupService( 3860): android.intent.action.SCREEN_ON
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): ACTION_SCREEN_ON
,V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=off, calling pid 973
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
D/GpsLocationProvider(  973): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/WifiController(  973): CMD_SCREEN_OFF 
D/WifiController(  973): shouldWifiStayAwake TRUE
,I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1804): clear
I/LEDService( 1804): updateLightsLocked : turn on led
D/LNfcService( 1787): action : android.intent.action.SCREEN_OFF
E/LEDService( 1804): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
E/LEDService( 1804): Can't handle this request of patternId:0
D/LEDHandler( 1804): RESTART MSG
D/NfcServiceNXP( 1787): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2637): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 22:15:19
D/WeatherService( 2637): 2 : ACTION screen off
D/WeatherService( 2637): 2 : TimeTick Receiver Unregister
D/WeatherService( 2637): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 22:15:19
D/AppCleanupService( 3860): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3860): AppUsageStatsSaveTask
,W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): ACTION_SCREEN_OFF
E/NxpNfcJni( 1787): getReconnectState = 0x0
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1787): getDefaultRoute
D/LNfcService( 1787): isRequireNfcCRouting() return true
D/LNfcService( 1787): isHCERoutingtoHost() return : true
D/NfcService( 1787): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): newParams.techmask= mTechMask: 0
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): screenState= 1
E/NxpNfcJni( 1787): getReconnectState = 0x0
,I/Sensors (  423): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1375): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{304c31f7 type 2 when 163445 com.android.systemui} when 163445
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1751): getCallState : 0
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1375): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1375): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 174295478374; DSPS: 5808937; Offset : -2989397712
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{23b4b864 type 2 when 182670 android} when 182670
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{5792acd type 2 when 183444 android} when 183444
,I/ClearcutLoggerApiImpl( 1734): disconnect managed GoogleApiClient
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{272fdf82 type 2 when 188746 com.google.android.gms} when 188746
,I/PhenotypeConfigurator( 1734): Scheduling Phenotype for one-off execution 2478 seconds from now (1454534149664)
,D/GetConfigurationSnapshotOperation( 1734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  973): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 1734): propertyValue:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  973): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  973): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  973): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  973): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 194296303210; DSPS: 6464324; Offset : -2989397632
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 214297045911; DSPS: 7119708; Offset : -2989386024
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 234297718039; DSPS: 7775090; Offset : -2989385647
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 254298468864; DSPS: 8430475; Offset : -2989397632
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 274299217815; DSPS: 9085859; Offset : -2989381104
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/jxcore-log( 5252): --= Surplus to requirements =--
I/jxcore-log( 5252): 
I/jxcore-log( 5252): ****TEST TOOK:  ms ****
I/jxcore-log( 5252): 
I/jxcore-log( 5252): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5252): 
,D/AndroidRuntime( 6726): 
D/AndroidRuntime( 6726): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6726): CheckJNI is OFF
,D/AndroidRuntime( 6726): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  973): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  973): Killing 5252:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,I/WindowState(  973): WIN DEATH: Window{34bf7d11 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  973): Focus left window: Window{34bf7d11 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  973): Window went away: Window{34bf7d11 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  973): Skipping PackageSetting{16ba88e1 com.example.hello/10317} due to missing metadata
,I/ActivityManager(  973):   Force finishing activity ActivityRecord{181ba64a u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  973): Display changed displayId=0
,D/DSDPConnection( 1751): Display #0 changed.
W/ActivityManager(  973): Spurious death for ProcessRecord{2ca32d32 5252:com.test.thalitest/u0a316}, curProc for 5252: null
,I/ActivityManager(  973): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  973):   Force finishing activity ActivityRecord{181ba64a u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  973): Duplicate finish request for ActivityRecord{181ba64a u0 com.test.thalitest/.MainActivity t222 f}
,D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  973): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1734): Ignoring removeGeofence because network location is disabled.
I/art     ( 1939): Explicit concurrent mark sweep GC freed 7759(470KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/19MB, paused 3.924ms total 92.786ms
,W/System.err( 3402): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3402): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3402): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3402): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3402): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3402): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3402): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3402): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3402): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3402): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3402): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3402): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  973): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6755 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 24.366ms
,I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.911ms
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
,I/Activity( 1878): Activity.onPostResume() called 
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.519ms
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework](  973): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  973): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  973): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  973): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  973): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2c625cd8,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  973): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  973): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  973): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  973): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  973): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  973): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2c625cd8,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  973): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  973): Focus entered window: Window{d621bf5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1375): handleShortcutListChanged...
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
,W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
D/KeyguardModel( 1375): handleShortcutListChanged...
,I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
W/ResourcesManager( 6755): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6755): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6755): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/art     (  973): Explicit concurrent mark sweep GC freed 59373(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 2.791ms total 332.206ms
I/art     (  973): WaitForGcToComplete blocked for 193.408ms for cause Explicit
,D/administrator(  973): Handling package changes for user 0
,I/art     (  973): Explicit concurrent mark sweep GC freed 5118(337KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.497ms total 239.104ms
,I/LGEmail ( 6755): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6755): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/InputMethodManagerService(  973): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  973): Got RemoteException sending setActive(false) notification to pid 5252 uid 10316
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
,D/AndroidRuntime( 6726): Shutting down VM
,I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/Timeline(  973): Timeline: Activity_windows_visible id: ActivityRecord{1fa354d2 u0 com.lge.launcher2/.Launcher t221} time:288132
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1595): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1878): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,I/NotificationService(  973): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  973): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  973): Receieved: android.intent.action.PACKAGE_REMOVED
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
,D/PhoneStatusBar( 1375): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  973): removeObsoleteFile: deleting file=222_task.xml
I/PackageChangeReceiver( 6755): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/AppUp4:PreloadHelper( 6376): added Exclude : com.test.thalitest
I/ActivityManager(  973): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6786 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  973): Killing 6419:com.android.contacts/u0a18 (adj 15): empty #11
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,W/ResourcesManager(  973): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume

```
